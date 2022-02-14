# Colon-Cancer-Detection
This model is exported from [Custom Vision Service](https://customvision.ai)

# Demo video
https://drive.google.com/file/d/1puqVowU9hDe0u0AOYd1jdfGoa31CeJFZ/view?usp=sharing

## Input specification
This model expects 320x320, 3-channel RGB images. Pixel values need to be in the range of [0-255].

## Output specification
There are three outputs from this model.

* detected_boxes
The detected bounding boxes. Each bounding box is represented as [x1, y1, x2, y2] where (x1, y1) and (x2, y2) are the coordinates of box corners.
* detected_scores
Probability for each detected boxes.
* detected_classes
The class index for the detected boxes.

# Reference
* [Custom Vision Service documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/custom-vision-service/)
* [Sample scripts](https://github.com/Azure-Samples/customvision-export-samples)
