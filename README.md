# Date Fruit Classification using Artificial Neural Networks (ANN)

## 📌 Overview
This repository contains a PyTorch-based Artificial Neural Network (ANN) designed to classify different varieties of date fruits based on their extracted morphological and shape features. 

## 📊 Dataset
The project uses the `DateFruit_Dataset.csv` which contains continuous numerical features describing the physical characteristics of the fruits. 
* **Input Features (34):** Area, Perimeter, Major/Minor Axis, Eccentricity, Solidity, Convex Area, Shape Factors, MeanRGB values, Kurtosis, Skewness, etc.
* **Target Variable:** `Class` (The variety of the date fruit, e.g., BERHI, DEGLET, DOKOL).

## 🧠 Model
The model is an Artificial Neural Network built using **PyTorch**. It processes the 34 tabular input features through fully connected layers, applying activation functions to learn the mappings required to accurately categorize the fruit classes.

## 🚀 Results
The trained PyTorch ANN model achieves excellent classification performance. On the test set, the model correctly predicted 167 out of 180 samples, yielding an **accuracy of ~92.78%**.

## 🛠️ Requirements
* Python 3.x
* PyTorch
* Pandas
* NumPy

## 💻 Usage
1. Clone this repository.
2. Ensure that `DateFruit_Dataset.csv` is in the same directory as the Jupyter Notebook.
3. Run the cells in `ANN_for_Classification.ipynb` to load the data, train the neural network, and view the evaluation metrics.
