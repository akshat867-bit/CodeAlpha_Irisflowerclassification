# 🌸 Iris Flower Classification using Machine Learning

A machine learning project that classifies Iris flowers into three species — **Setosa, Versicolor, and Virginica** — using flower measurements and Scikit-learn.

## 📌 Project Overview

The Iris Flower Classification project uses supervised machine learning to predict the species of an Iris flower based on its physical measurements. Different classification algorithms are trained and evaluated to understand their performance.

## 🎯 Objectives

- Understand the machine learning classification workflow.
- Explore and visualize the Iris dataset.
- Preprocess data and train classification models.
- Evaluate model performance using accuracy and other classification metrics.
- Predict the species of a flower using its measurements.

## 📊 Dataset

The dataset is available on Kaggle:

**Dataset:** [Iris Dataset on Kaggle](https://www.kaggle.com/datasets/saurabh00007/iriscsv)

It contains measurements of Iris flowers belonging to three species:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

### Features

| Feature | Description |
|---|---|
| Sepal Length | Length of the sepal |
| Sepal Width | Width of the sepal |
| Petal Length | Length of the petal |
| Petal Width | Width of the petal |
| Species | Target class to predict |

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## ⚙️ Project Workflow

1. Load the dataset.
2. Clean and preprocess the data.
3. Perform exploratory data analysis (EDA).
4. Visualize feature distributions and relationships.
5. Split the dataset into training and testing sets.
6. Train machine learning classification models.
7. Evaluate model performance.
8. Predict the species of a new Iris flower.

## 🤖 Machine Learning

The project uses classification algorithms to learn patterns from the flower measurements and predict the corresponding species.

Model performance can be evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🚀 How to Run the Project

### Option 1: Google Colab

1. Download the notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload `Iris_Flower_Classification.ipynb`.
4. Upload the dataset when prompted by the notebook.
5. Run the cells sequentially.

### Option 2: Run Locally

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/iris-flower-classification.git
```

Navigate to the project folder:

```bash
cd iris-flower-classification
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

Open the notebook:

```bash
jupyter notebook Iris_Flower_Classification.ipynb
```

Follow the notebook instructions to load the dataset and train the model.

## 📈 Results

The trained model predicts the Iris species using sepal and petal measurements. Its performance is evaluated using classification metrics and a confusion matrix.

**Note:** Actual accuracy and evaluation results depend on the model configuration and train-test split. Refer to the notebook output for the measured results.


