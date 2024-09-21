# 🐶🐱 Dogs vs Cats Classification with ResNet

Welcome to my **Dogs vs Cats** image classification project! In this project, I aimed to explore Convolutional Neural Networks (CNNs) using a pre-trained ResNet model to classify images of dogs and cats. The project achieved **98% accuracy**.

## 🔍 Overview
The primary goal was to understand how CNN architectures, particularly ResNet, can be used for image classification. Additionally, I learned how to handle raw data, manage datasets on Kaggle, and apply various techniques like data augmentation and learning rate schedules.

[Check the Kaggle notebook here](https://www.kaggle.com/code/alaagaberh/dogs-vs-cats-resnet-98)

## 📋 Table of Contents
- [Unzip and Load the Data](#unzip-and-load-the-data)
- [Get the Images into a DataFrame](#get-the-images-into-a-dataframe)
- [Split the Data](#split-the-data)
- [Image Data Generator](#image-data-generator)
- [Show Sample Data](#show-sample-data)
- [ResNet Architecture](#resnet-architecture)
- [Model Callbacks](#model-callbacks)
- [Evaluate the Model](#evaluate-the-model)
- [Model Misclassifications](#model-misclassifications)
- [Plot Top N Misclassifications](#plot-top-n-misclassifications)
- [Predictions](#predictions)
- [Submission](#submission)

## 🚀 Key Highlights

### 1. Data Augmentation 💡
- Used **data augmentation** to make the model more invariant to variations in the dataset. 
- Helped improve generalization and avoid overfitting.

### 2. Learning Rate Tuning 🔑
- Fine-tuned the model with a **learning rate schedule (ReduceLROnPlateau)**.
- Applied **early stopping** to optimize the performance.

### 3. Model Checkpoints 📍
- Used **model checkpoints** to save the best weights during training.
- Ensured optimal performance by saving weights at the best scores during training.

### 4. Transfer Learning 🧠
- Leveraged **transfer learning** by using the **pre-trained ResNet architecture**.
- This made training faster and more efficient.

### 5. Kaggle Data Management 📂
- Learned to handle raw datasets on Kaggle.
- Managed data effectively, including unzipping files and organizing the workflow.

## 📈 Results
- Achieved **98% accuracy** on the test dataset.
- Analyzed and visualized misclassifications to improve the model’s robustness.

## 🔬 Model Evaluation
- Investigated the biggest **model misclassifications**.
- Visualized the top N misclassifications to understand where the model struggled.

## ⚙️ Tech Stack
- **Python**
- **Keras** (with TensorFlow backend)
- **ResNet50**
- **Pandas**, **Numpy**, **Matplotlib**

## 📊 Conclusion
Working on this project provided hands-on experience with:
- **Image classification**
- **CNNs**
- **Transfer learning**

I'm excited to continue exploring deep learning architectures and improving my models. 😄
