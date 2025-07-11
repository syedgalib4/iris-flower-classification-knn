# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

This project is part of my **AI & ML Internship (Week 3)**, where I implement a basic machine learning model to classify iris flowers into three species using the **K-Nearest Neighbors (KNN)** algorithm.

---

## 📌 Objective

To build a classification model that can predict the **species of an iris flower** based on the following features:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 📁 Dataset

- Used the built-in **Iris dataset** from `sklearn.datasets`
- Contains 150 samples from three species: **Setosa**, **Versicolor**, and **Virginica**

---

## 🔧 Tools & Libraries

- Python
- Google Colab / Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `sklearn`

---

## 📊 Features Used

| Feature        | Description          |
|----------------|----------------------|
| sepal length   | Length of the sepal  |
| sepal width    | Width of the sepal   |
| petal length   | Length of the petal  |
| petal width    | Width of the petal   |

---

## ✅ Steps Implemented

1. Imported the Iris dataset using `sklearn.datasets`
2. Converted it into a DataFrame using `pandas`
3. Explored the dataset with:
   - `head()` method
   - Pairplots using `seaborn`
   - Histograms
4. Split data into training and testing sets using `train_test_split`
5. Applied the **K-Nearest Neighbors (KNN)** algorithm (k=3)
6. Trained the model and predicted results
7. Evaluated the model using:
   - Accuracy Score
   - Confusion Matrix

---

## 📈 Results

- **Accuracy Achieved**: _~96%_ (depending on k-value)
- **Best k-value** found using a loop from 1 to 10

---

## 📌 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
2. Make sure the required libraries are installed.
3. Run each cell step-by-step to see the outputs.

---

## 📝 Submission

- This notebook is submitted as part of the **Week 3 assignment** for the AI & ML internship.
- Uploaded on **GitHub** and submitted via the Google Form.

---

## 🙋‍♀️ Author

Syed Galib
B.Tech - CSE | AI & ML Intern  
