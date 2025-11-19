# 🌼 Iris Flower Classification  
A Machine Learning project using the classic Iris dataset to classify flower species based on sepal and petal measurements.

---

## 📌 Project Overview
The Iris dataset is one of the most famous datasets in machine learning.  
The goal of this project is to build a model that predicts the species of an Iris flower using:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

This notebook includes:
- Data loading  
- Exploratory Data Analysis (EDA)  
- Visualizations  
- Model training  
- Model evaluation  

---

## 📁 Dataset Information
The dataset contains **150 samples**, classified into **3 species**:

- *Iris-setosa*  
- *Iris-versicolor*  
- *Iris-virginica*  

Each sample includes 4 numerical features:
| Feature | Description |
|---------|-------------|
| sepal_length | Sepal length in cm |
| sepal_width  | Sepal width in cm |
| petal_length | Petal length in cm |
| petal_width  | Petal width in cm |

Dataset source:  
🔗 https://archive.ics.uci.edu/dataset/53/iris

---

## 🚀 Steps Covered in the Notebook

### 1️⃣ Importing Libraries  
Using NumPy, Pandas, Matplotlib, Seaborn & Scikit-learn.

### 2️⃣ Data Exploration  
- Dataset shape  
- Summary statistics  
- Checking for missing values  

### 3️⃣ Visualizations  
- Pairplot  
- Heatmap  
- Distribution plots  

### 4️⃣ Model Building  
Trained different ML models:
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree  
- Random Forest  

### 5️⃣ Model Evaluation  
Used metrics like:
- Accuracy  
- Confusion Matrix  
- Classification Report  

---

## 🏆 Best Model Result
The **Random Forest Classifier** typically gives **95–98% accuracy** on this dataset.

---

## 📦 Requirements
Install dependencies with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
