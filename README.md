# Student Performance Prediction 📊

## Project Overview

This project predicts student academic performance using machine learning. The model analyzes various factors such as demographic information, study habits, and academic history to estimate student performance.

The dataset used in this project is downloaded directly from **Kaggle** and processed using Python libraries.

---

## Dataset

Dataset: **Student Alcohol Consumption Dataset**

Source: Kaggle

The dataset contains information about students including:

* School
* Gender
* Age
* Family size
* Parents' education
* Study time
* Absences
* Previous grades (G1, G2)
* Final grade (G3)

These features help analyze patterns that influence student performance.

---

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Kaggle API
* Google Colab

---

## Project Workflow

### 1. Dataset Download

The dataset is downloaded directly from Kaggle using the Kaggle API.

### 2. Data Extraction

The downloaded ZIP file is extracted to access the dataset files.

### 3. Data Loading

The dataset is loaded using **Pandas** for further analysis.

### 4. Data Preprocessing

Features and target variables are prepared for machine learning.

### 5. Train-Test Split

The dataset is divided into:

* Training Data (80%)
* Testing Data (20%)

### 6. Model Training

A **Logistic Regression** model is trained using the training dataset.

### 7. Prediction

The trained model predicts student performance on the test dataset.

### 8. Model Evaluation

Model performance is evaluated using:

* Accuracy Score
* Confusion Matrix

---

## Machine Learning Model

Algorithm used:

Logistic Regression

The model learns patterns from student data to predict academic outcomes.

---

## Results

The model predicts student performance and evaluates its accuracy using:

* Accuracy Score
* Confusion Matrix Visualization

These results help understand how well the model performs on unseen data.

---

## Project Structure

```
Student-Performance-Prediction
│
├── Student_Performance_Project.ipynb
├── student-mat.csv
├── kaggle.json
└── README.md
```

---

