# Spleen Image Segmentation

## Project Overview
This repository contains a Jupyter notebook that implements a segmentation algorithm for spleen imaging as part of the medical segmentation decathlon. The project utilizes a U-Net architecture for volumetric image segmentation, aiming to accurately delineate the spleen in CT images.

## Data
The dataset consists of 41 volumetric CT images along with their corresponding labels:
- `imagesTr`: Training images.
- `labelsTr`: Corresponding labels for the training images.
- `imagesTs`: Test images (not used unless specified).

The data is derived from the Medical Segmentation Decathlon, focusing on the spleen segmentation task.

## Project Sections
- **Part 1**: Basic segmentation without augmentation.
- **Part 2**: Implementation of affine transformations and elastic deformations as augmentation techniques.
- **Part 3**: Optimization of parameters including the loss function, learning rate, and network parameters.
- **Part 4**: Use of unlabeled data for augmentation consistency training.
- **Part 5**: Implementation of uncertainty estimation using Dropout to visualize and analyze areas of high uncertainty in segmentation predictions.

## Results
The repo includes a comprehensive report of the training processes, the application of augmentations, parameter optimizations, and the performance of the model using different metrics. A visualization of uncertainty estimates in segmentation are also provided in the notebook and the report.

