# project2
# Iris Flower Classification System 🌸

A web-based Machine Learning application for classifying Iris flowers using KNN and Naive Bayes algorithms.

---

## Overview

This project predicts the species of an Iris flower using four flower measurements:

- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

Users can select a machine learning model and obtain:

- Predicted flower species
- Training accuracy
- Testing accuracy
- Confusion matrix
- Classification report

---

## Project Preview

### Main Interface

![Main Interface](images/home.png)

### Prediction Results

![Prediction Results](images/result.png)

### Confusion Matrix

![Confusion Matrix](images/confusion_matrix.png)

---

## Features

✅ Interactive UI design

✅ KNN model support

✅ Naive Bayes model support

✅ Dynamic prediction system

✅ Training accuracy visualization

✅ Testing accuracy visualization

✅ Confusion matrix display

✅ Classification report display

✅ Responsive design

---

## Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript
- Font Awesome

### Backend
- Python
- Flask

### Machine Learning
- Scikit-learn
- Pandas
- NumPy

---

## Input Features

The model accepts four flower measurements:

| Feature | Description |
|-----------|-------------|
| Sepal Length | Length of sepal |
| Sepal Width | Width of sepal |
| Petal Length | Length of petal |
| Petal Width | Width of petal |

---

## Models Used

### KNN (K-Nearest Neighbors)

- Classifies data based on nearest neighbors
- Works well for Iris datasets
- Simple and effective algorithm

### Naive Bayes

- Probabilistic classification algorithm
- Fast prediction speed
- Assumes feature independence

---

## Project Structure

```bash
Iris-Flower-Classification/
│
├── app.py
├── model.py
├── templates/
│   └── index.html
│
├── static/
│   ├── images/
│   │   ├── home.png
│   │   ├── result.png
│   │   └── confusion_matrix.png
│
├── README.md
└── requirements.txt
```

---

## How to Run

### Step 1: Clone Repository

```bash
git clone https://github.com/your-username/iris-flower-classification.git
```

### Step 2: Install Libraries

```bash
pip install -r requirements.txt
```

### Step 3: Run Flask Application

```bash
python app.py
```

### Step 4: Open Browser

```bash
http://127.0.0.1:5000/
```

---

## Output Example

```text
Predicted Flower: Iris Setosa

Training Accuracy: 97%

Testing Accuracy: 95%
```

---

## Future Improvements

- Add more machine learning algorithms
- Add charts and graphs
- Deploy to cloud platforms
- Store prediction history
- Add dataset upload feature
- Improve UI animations

---

## Dataset Information

Dataset: Iris Dataset

Classes:

- Iris Setosa
- Iris Versicolor
- Iris Virginica

Features: 4

Total Samples: 150

---

## Author

Developed using Machine Learning and Flask for Iris flower prediction.
