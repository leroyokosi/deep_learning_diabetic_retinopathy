# Project Overview:
This project explored the application of deep learning models for the image classification of diabetic retinopathy. Three popular pre-trained models, namely ResNet, VGG, and AlexNet, were evaluated and compared based on their performance metrics.

The goal is to provide an automated solution for early detection of diabetic retinopathy, a leading cause of blindness.

# Usage:
This project offers a powerful tool for the medical field, particularly in diabetic retinopathy diagnosis. It provides an automated, efficient, and accurate solution for early detection, making it valuable for healthcare organizations and clinics. Medical professionals can integrate this deep learning model into their screening programs, improving patient care and reducing the risk of vision loss. Additionally, it supports telemedicine, research, education, and customization to meet the specific needs of medical institutions. This project represents a significant advancement in the application of technology to enhance medical diagnostics.

# Dependencies:
- Python 3.x
- PyTorch (GPU access)

Install the required packages:
```
pip install opendataset
pip install torch
```

# Dataset:
The images consist of Gaussian-filtered retina scan images to detect diabetic retinopathy. The original dataset is available at APTOS 2019 Blindness Detection. The dataset is grouped into five categories with the respective images:

0 - No_DR
1 - Mild
2 - Moderate
3 - Severe
4 - Proliferate_DR

Dataset can be found https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-gaussian-filtered 
Be sure to have a Kaggle API key for downloading.


# Data Augmentation:
- Balancing Data: Augmented data for balanced class distribution with rotations, flips, and affine transforms.
- Splitting Data: Organized data into training, validation, and test sets in separate folders.
- Applying Transforms: Prepared data for ResNet, AlexNet, and VGG by resizing and normalizing images.
- Image to Tensor: Converted pre-processed images to tensors for deep learning compatibility.
- Batch Processing: Utilized a batch size of 32 for efficient data loading during training and testing.


# Model Evaluation
This project uses the Confusion Matrix, Accuracy, F1 Score, Recall, and Precision as quantitative measures for analyzing and comparing models.



