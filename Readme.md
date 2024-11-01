# GAN for Brain Tumor MRI Image Generation

This repository contains the implementation of a Generative Adversarial Network (GAN) for generating synthetic brain tumor MRI images. The project aims to aid in medical imaging research by creating a dataset of diverse and realistic tumor images, potentially improving data availability for training machine learning models.

## Overview

Medical image datasets can be limited due to privacy concerns and the costs of acquiring labeled images. This GAN model generates synthetic brain MRI images with realistic tumor patterns, providing a solution for augmenting existing datasets. Synthetic images generated by this model can be used to train and validate deep learning algorithms for tumor detection and diagnosis.

## Features

- **Generative Adversarial Network (GAN)**: Implements a GAN architecture tailored for MRI images with tumors, focusing on realistic and detailed tumor structures.
- **Data Augmentation**: Generates high-quality synthetic images, supporting data augmentation for training models in tumor classification and detection tasks.
- **Customizable Parameters**: The notebook allows easy customization of parameters such as the number of epochs, learning rate, and model layers.
- **Evaluation Metrics**: Includes loss metrics for both the generator and discriminator models to track model performance over time.

## Dataset

The model is trained on a structured brain tumor MRI dataset with four classes of images across training and testing sets:


Each folder within `Training` and `Testing` contains MRI images belonging to one of the four categories: `notumor`, `glioma`, `meningioma`, and `pituitary`.

## Results

The model generates synthetic MRI images with realistic tumor patterns. Below are some sample images generated by the GAN model, showcasing its ability to replicate diverse tumor structures.

## License 

Neeraj Jaiswal
