# Aerial Image Segmentation using PyTorch

## Overview

This repository contains a deep learning project for aerial image segmentation using PyTorch. 

## Features

- Preprocessing of aerial image datasets
- Implementation of deep learning models for segmentation
- Training pipeline using PyTorch

## Dataset

The project uses an open-source aerial image segmentation dataset. The dataset consists of high-resolution images, with corresponding ground truth segmentation masks.

### Full Dataset

https://www.cs.toronto.edu/~vmnih/data/

```
@phdthesis{MnihThesis,
author = {Volodymyr Mnih},
title = {Machine Learning for Aerial Image Labeling},
school = {University of Toronto},
year = {2013}
}
```

## Prerequisites

Before setting up the project, ensure you have the following installed:

- PyTorch
- OpenCV
- Albumentations

## Files in Repository

- <b>Aerial_Image_Segmentation.ipynb</b> - Jupyter Notebook containing the full pipeline for data preprocessing, model training, evaluation, and visualization.

- <b>Aerial_Img_Segmentation_Parameters.pt</b> - Saved PyTorch model parameters for inference.

## Usage
To train or evaluate the model, open the Jupyter Notebook:

```bash
jupyter notebook Aerial_Image_Segmentation.ipynb
```
Follow the instructions in the notebook to train the model or load the pre-trained weights for inference.

## Contributions

Contributions are welcome! Feel free to submit issues or pull requests to improve the project.