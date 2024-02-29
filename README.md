# Ship Detection under Complex Background

## Overview

This project addresses ship detection in complex backgrounds using a saliency-based algorithm for background removal and Mask R-CNN for ship prediction. The saliency algorithm iteratively filters out the background, while Mask R-CNN accurately predicts ship instances in images.

## Saliency-Based Background Filtering

The algorithm employs Otsu's method for thresholding, iteratively processes image regions, and changes the background to the most frequent pixel value in ship-absent regions.

## Mask R-CNN for Ship Prediction

The project integrates Mask R-CNN, a deep learning model capable of segmenting and detecting ship instances in images.

## Usage

- **Saliency-Based Filtering**: Use the `filter_image` function by providing the original image and parameters for effective background removal.

- **Mask R-CNN Prediction**: Integrate the Mask R-CNN model for accurate ship prediction.

## Dependencies

Ensure the installation of necessary dependencies like NumPy and scikit-image.
