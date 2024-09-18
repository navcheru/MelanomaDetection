# Melanoma Detection Using CNN
> This project aims to build a custom convolutional neural network (CNN) model to accurately detect melanoma, a type of skin cancer, from images of oncological diseases.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- The goal of this project is to develop a machine learning model capable of classifying skin lesions into 9 categories of oncological diseases, including melanoma.
- Melanoma accounts for 75% of skin cancer deaths, and early detection is critical for improving survival rates. This model can assist dermatologists by providing accurate predictions and reducing manual diagnosis time.
- The dataset used in this project contains 2,357 images of benign and malignant skin conditions, including melanoma, collected from the International Skin Imaging Collaboration (ISIC).

### Dataset contains the following classes:
1. Actinic keratosis
2. Basal cell carcinoma
3. Dermatofibroma
4. Melanoma
5. Nevus
6. Pigmented benign keratosis
7. Seborrheic keratosis
8. Squamous cell carcinoma
9. Vascular lesion

## Conclusions
- The custom CNN model successfully classified skin lesion images into 9 categories.
- Data augmentation strategies helped reduce overfitting, improving the model’s generalization on unseen data.
- Handling class imbalances with augmentation techniques improved the model's performance on underrepresented classes.
- The model's performance can be further enhanced with additional data and more sophisticated network architectures.

## Technologies Used
- Python 3.8
- TensorFlow 2.8.0
- Keras 2.8.0
- Augmentor 0.2.8
- NumPy 1.21.5
- Matplotlib 3.5.1

## Acknowledgements
- This project was inspired by the need for an automated system for melanoma detection to assist dermatologists.
- The dataset is provided by the International Skin Imaging Collaboration (ISIC).
- This project was based on techniques learned from TensorFlow’s documentation and various online tutorials.

## Contact
Created by [@kajalmahata123] - feel free to contact me!
