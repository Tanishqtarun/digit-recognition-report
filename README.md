# digit-recognition-report

# Handwritten Digit Recognition Project

This project explores various machine learning models to recognize handwritten digits using the MNIST dataset. The aim is to evaluate and compare model performance based on accuracy and interpretability to guide future improvements.

## 🔗 Live Demo

👉 [Try the Digit Recognition Web App](https://maneprajakta.github.io/Digit_Recognition_Web_App/)

## 👥 Authors

Tanishq, Adwith, Srijith, Venu, Srikar, Arjun

---

## 📊 Abstract

We implemented and tested five different machine learning models on the MNIST dataset:

- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Linear Regression
- Decision Tree

Each model was trained and evaluated on a subset of the MNIST dataset. We compared them based on prediction accuracy and model interpretability.

---

## 🗃 Dataset Description

- **Dataset:** MNIST (28x28 grayscale images of digits 0–9)
- **Total samples used:** 10,000
  - 8,000 for training
  - 2,000 for testing
- **Preprocessing:**
  - Normalized pixel values to the range [0, 1]

---

## 🧠 Models & Their Principles

### 1. Support Vector Machine (SVM)
- Uses hyperplanes in high-dimensional space to classify digits
- RBF kernel used for handling non-linear relationships

### 2. K-Nearest Neighbors (KNN)
- Classifies digits by majority vote among the 'k' nearest neighbors in feature space

### 3. Gaussian Naive Bayes
- Assumes feature independence and normal distribution
- Fast and efficient, but may struggle with complex data

### 4. Linear Regression
- Predicts continuous values, then maps them to the nearest digit class

### 5. Decision Tree
- Builds a tree structure of decisions based on feature thresholds
- Interpretable but prone to overfitting

---

## 📈 Results Summary

| Model             | Accuracy (%) |
|------------------|--------------|
| SVM              | 93.7%        |
| KNN              | 91.2%        |
| Naive Bayes      | 83.5%        |
| Linear Regression| 78.4%        |
| Decision Tree    | 88.1%        |

---

## ✅ Conclusion

- **SVM** achieved the highest accuracy and is suitable for high-performance applications.
- **KNN** performed well with simplicity but can be computationally expensive.
- **Naive Bayes** is fast but less accurate for image data.
- **Linear Regression** is not ideal for classification tasks.
- **Decision Tree** provides good interpretability with decent accuracy.

---

## 🚀 Future Work

- Test with larger datasets or additional models (e.g., Random Forests, Neural Networks)
- Hyperparameter tuning for better performance
- Incorporate cross-validation for more robust evaluation

---

## 📁 Project Structure (Suggestion)

