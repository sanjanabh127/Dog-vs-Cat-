# 🐶 Dog vs. Cat Classification using CNN
 ![Python](https://img.shields.io/badge/Python-3.8+-blue.svg?logo=python&logoColor=white) 
 ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.6+-ff6f00.svg?logo=tensorflow&logoColor=white) 
 ![Keras](https://img.shields.io/badge/Keras-2.6+-D00000.svg?logo=keras&logoColor=white) 
 ![NumPy](https://img.shields.io/badge/NumPy-1.x-013243.svg?logo=numpy&logoColor=white) 
 ![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-013243.svg?logo=plotly&logoColor=white) 
 ![OpenCV](https://img.shields.io/badge/OpenCV-4.x-5C3EE8.svg?logo=opencv&logoColor=white) 


##  Overview
This project uses a Convolutional Neural Network (CNN) to classify images of dogs and cats. The model is trained on the Kaggle dataset to distinguish between the two classes with high accuracy.

## 📦 Dataset
- **Dataset Name**: Cats vs Dogs Training8000Test2000  
- **Kaggle Link**: [https://www.kaggle.com/datasets/dhirensk/cats-vs-dogs-training8000test2000](https://www.kaggle.com/datasets/dhirensk/cats-vs-dogs-training8000test2000)  

The dataset contains 10,000 images:  
- **Training Set**: 8,000 images  
- **Test Set**: 2,000 images  

Images are organized into

`train/cats`

`train/dogs`

`test/cats`

`test/dogs`.

## 🧠 Model Architecture
The CNN model is built using Keras with TensorFlow backend and consists of:  
- Convolutional layers for feature extraction  
- MaxPooling layers to reduce spatial dimensions  
- Flatten layer to convert 2D matrices into 1D vectors  
- Dense layers for classification  

