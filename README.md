# Malaria-Detection
### Introduction 
As we all know Malaria is caused by a Mosquito Bite resulting in Infected Cells by Parasite and not by a Virus, it can be cured if known early.
Our Model aims to detect Cells which are Parasitized or not using a subset of Machine Learning which is known as Convolutional Neural Network.

#### What is Neural Network ?
Neural networks, also known as Artificial Neural Networks (ANNs) or Simulated Neural Networks (SNNs), are a subset of machine learning and are at the heart of deep learning algorithms. Their name and structure are inspired by the human brain, mimicking the way that biological neurons signal to one another.

### Steps to solve the problem
1. Importing Libraries - We have used python libraries like Pandas, NumPy, Matplotlib, Seaborn, Tensorflow, Scikit-learn, etc.
   1. Pandas and NumPy for Data Preprocessing
   2. Matplotlib and Seaborn for display charts and graphs.
   3. Tensorflow and Scikit-learn for Training the model.
2. Loading the Data - We have provided a Dataset from www.kaggle.com.
3. Data Preprocessing - Converting the images to a NumPy array and performing some Normalization for easy calculations.
4. Data augmentation - Artificially increasing the amount of data by generating new data points from existing data.
5. Ploting images and its labels to understand how does an infected cell and uninfected cell looks like.
6. Spliting data in Train , Evaluation and Test set
7. Creating a Convolution Neural Network Model.
8. Training the data on Train data.
9. Evaluating on evaluation data.
10. Predicting on Test data.
11. Ploting the predicted image and its respective True value and predicted value.

### How it works ?
The data provided to the model contains contains images of the Infected and Uninfected cells we will preprocess the data and will further gets splits into Train, Test and Evaluation. Then a CNN model is created and data is trained on that model, it will be evaluated and will check the accuracy of the model. In this we have achieved the accuracy of 95%. Later that it will be checked on Test Data and Final result will be shown.
