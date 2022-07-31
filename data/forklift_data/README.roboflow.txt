
Forklift - v5 augmented-ACCURATE_model
==============================

This dataset was exported via roboflow.com on July 19, 2022 at 11:03 AM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 1011 images.
Forklift are annotated in YOLO v7 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 416x416 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Equal probability of one of the following 90-degree rotations: none, clockwise, counter-clockwise, upside-down
* Random rotation of between -5 and +5 degrees
* Random brigthness adjustment of between -10 and +10 percent
* Random exposure adjustment of between -15 and +15 percent
* Random Gaussian blur of between 0 and 1 pixels


