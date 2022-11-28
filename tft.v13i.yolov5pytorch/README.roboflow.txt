
tft - v13 2022-11-28 11:58pm
==============================

This dataset was exported via roboflow.com on November 28, 2022 at 3:02 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 834 images.
TFT-CHAMPIONS are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Resize to 416x416 (Fit within)

The following augmentation was applied to create 3 versions of each source image:
* Randomly crop between 0 and 8 percent of the image
* Random brigthness adjustment of between -39 and +39 percent

The following transformations were applied to the bounding boxes of each image:
* Random brigthness adjustment of between -25 and +25 percent
* Salt and pepper noise was applied to 5 percent of pixels


