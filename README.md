# Iris Flower Classification 🌸

![Iris Classification Banner](https://upload.wikimedia.org/wikipedia/commons/4/41/Iris_versicolor_3.jpg)

This repository contains my first task for the **CodeAlpha Data Science Internship**: Iris Flower Classification.

## 📌 Project Overview
The objective of this project is to build a machine learning model capable of classifying Iris flowers into three distinct species: *Setosa*, *Versicolor*, and *Virginica*, based on their sepal and petal dimensions. It serves as a foundational project demonstrating data manipulation, exploratory data analysis (EDA), and basic machine learning classification using Python.

## 🛠️ Technologies Used
- **Python 3.x**
- **Pandas & NumPy** (Data manipulation)
- **Matplotlib & Seaborn** (Data visualization)
- **Scikit-Learn** (Machine Learning algorithms & evaluation)

## 📊 Methodology
1. **Data Loading**: Loaded the classic Iris dataset provided directly by `sklearn.datasets`.
2. **Exploratory Data Analysis (EDA)**: Visualized feature distributions and correlations using `seaborn.pairplot` and `seaborn.heatmap`.
3. **Data Preprocessing**: Split the data into training (80%) and testing (20%) sets. Scaled the features using `StandardScaler`.
4. **Modeling**: Trained a `RandomForestClassifier`.
5. **Evaluation**: Evaluated the model using Accuracy Score, Confusion Matrix, and a detailed Classification Report.

## 📈 Results
- The Random Forest model achieved a high accuracy (typically ~96-100% depending on the split) on the test dataset.
- The model correctly distinguished *Setosa* with 100% precision and recall, as it is linearly separable from the other two species.

## 🚀 How to Run
1. Clone this repository.
2. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Open `Iris_Flower_Classification.ipynb` using Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook Iris_Flower_Classification.ipynb
   ```
4. Run all the cells sequentially.

---
**Author**: [Muhammad Alfarizi Ramadhiyansa]  
**Internship**: CodeAlpha - Data Science Intern
