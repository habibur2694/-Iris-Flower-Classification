#  Iris Flower Classification

##  Project Overview

This project is a basic Machine Learning classification project using the famous Iris Flower dataset.

The goal of this project is to train a Machine Learning model that can classify Iris flowers into three different species based on their flower measurements.

The three species are:

- Setosa
- Versicolor
- Virginica

This project is implemented using Python and Scikit-learn in Google Colab.

---

##  Objectives

The main objectives of this project are:

- Understand the Iris dataset.
- Explore and visualize the dataset.
- Separate input features and target labels.
- Split the dataset into training and testing sets.
- Apply feature scaling.
- Train a Machine Learning classification model.
- Predict Iris flower species.
- Evaluate model performance using accuracy.
- Generate a classification report.
- Analyze the confusion matrix.
- Predict the species of a new flower using its measurements.

---

## 📊 Dataset

The Iris dataset contains **150 flower samples**.

Each sample contains four measurements:

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal in centimeters |
| Sepal Width | Width of the sepal in centimeters |
| Petal Length | Length of the petal in centimeters |
| Petal Width | Width of the petal in centimeters |

The target variable contains three classes:

| Class | Species |
|---|---|
| 0 | Setosa |
| 1 | Versicolor |
| 2 | Virginica |

Each species contains 50 samples.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🤖 Machine Learning Algorithm

This project uses the:

### K-Nearest Neighbors (KNN)

KNN is a supervised Machine Learning algorithm commonly used for classification problems.

In this project, the model uses the measurements of an Iris flower to determine which species it belongs to.

The model is configured with:

```python
KNeighborsClassifier(n_neighbors=5)
