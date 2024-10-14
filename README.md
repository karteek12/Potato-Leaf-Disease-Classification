# Potato-Leaf-Disease-Detection using CNN

# Overview
This project aims to classify potato leaf diseases using a Convolutional Neural Network (CNN). The model is designed to accurately identify various diseases affecting potato plants, thereby assisting farmers in taking timely action to mitigate crop loss.

# Table of Contents
* Background
* Dataset
* Technologies Used
* Model Architecture
* Installation
* Results
* Future Work
* License

# Background
Potato crops are susceptible to various diseases, which can significantly affect yield and quality. Early detection and accurate classification of these diseases are crucial for effective management. This project utilizes deep learning techniques to provide an automated solution for disease identification.

# Dataset
The dataset used in this project consists of images of potato leaves (Total of 2152 images) , labeled with different disease categories(Mainly 3 Categories). The images are preprocessed to ensure consistency in size and quality.

# Technologies Used
* Python
* TensorFlow
* Keras


# Model Architecture
The CNN model is structured as follows:

* **Input Layer**: Accepts images of potato leaves.
* **Convolutional Layers**: Multiple convolutional layers for feature extraction.
* **Pooling Layers**: Max pooling layers to reduce dimensionality.
* **Flatten Layer**: Converts the 2D feature maps into a 1D vector.
* **Fully Connected Layers**: Dense layers for classification.
* **Output Layer**: Softmax activation to output probabilities for each disease category.
# Installation
To set up the project, follow these steps:

1.Clone the repository:
```
git clone [repository-link]
cd potato-leaf-disease-classification
```
2.Install the required packages:
```
pip install -r requirements.txt
```

# Results
The model achieved an accuracy of 95.33% on the test dataset.


# Future Work
* Explore transfer learning techniques to improve model performance.
* Develop a user-friendly interface for real-time disease classification.
# License
This project is licensed under the MIT License. See the LICENSE file for more details.
