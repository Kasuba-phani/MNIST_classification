# MNIST_classification
This project focuses on classifying handwritten digits (0–9) using traditional machine learning algorithms on the MNIST dataset from Kaggle. Instead of deep learning, we compare the performance of several classical classifiers like XGBoost, SVM, Random Forest, and more using F1-score as the evaluation metric.

---

## 📊 Dataset

- Source: [Kaggle MNIST Dataset](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv)
- Contains 70,000 grayscale images (28x28 pixels) of digits 0–9
- Each image is flattened into a 784-dimensional feature vector

---

## 🧠 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- AdaBoost
- XGBoost

---

## 🧪 Evaluation

Model performance was evaluated using **F1-score**. Below are the top-performing classifiers:

| Model              | F1-Score |
|-------------------|----------|
| XGBoost           | 0.989    |
| Random Forest     | 0.986    |
| SVM               | 0.978    |
| KNN               | 0.967    |

📊 ![F1 Scores](images/f1_scores.png)

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- PIL (for image handling)
- Jupyter Notebook

---


## 🚀 Future Improvements

- Add PCA for dimensionality reduction
- Use GridSearchCV for hyperparameter tuning
- Transition to CNN models for deep learning-based digit recognition

---

## 👨‍💻 Author

**Phanidhar Venkata Naga Kasuba**  
MS in Data Analytics, Webster University  
📫 Email: pkasubavenkatana@webster.edu  
🔗 [LinkedIn](www.linkedin.com/in/phanidhar-kasuba-venkata-naga)

---
