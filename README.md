# 📊 Big Data Analytics Assignment using PySpark

## 📌 Overview

This project demonstrates the implementation of three fundamental data analytics techniques using **PySpark MLlib**:

* ✅ Classification using Logistic Regression
* ✅ Clustering using K-Means
* ✅ Recommendation System using ALS (Collaborative Filtering)

All implementations are executed in **Google Colab**.

---

## 🚀 Technologies Used

* Python 🐍
* PySpark ⚡
* Google Colab ☁️
* Pandas 🧮
* Matplotlib 📈

---

## 📂 Datasets Used

### 1️⃣ Classification

* **Dataset Name:** Titanic Dataset
* **Source:** Data Science Dojo
* **Link:** [https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv](https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv)
* **Description:**
  Predicts whether a passenger survived based on features like age, fare, and class.

---

### 2️⃣ Clustering

* **Dataset Name:** Wholesale Customers Dataset
* **Source:** UCI / Machine Learning Repository
* **Link:** [https://raw.githubusercontent.com/jbrownlee/Datasets/master/wholesale-customers.csv](https://raw.githubusercontent.com/jbrownlee/Datasets/master/wholesale-customers.csv)
* **Description:**
  Segments customers based on spending patterns across product categories.

---

### 3️⃣ Recommendation System

* **Dataset Name:** Movie Ratings Dataset (IMDb-style)
* **Source:** Public GitHub Dataset
* **Link:** [https://raw.githubusercontent.com/raunakramteke/Data-Science-Assignment/master/movie_ratings.csv](https://raw.githubusercontent.com/raunakramteke/Data-Science-Assignment/master/movie_ratings.csv)
* **Description:**
  Contains user–movie–rating interactions used for building a recommendation system.

---

## ⚙️ Implementation Details

### 🔹 1. Classification (Logistic Regression)

* Data preprocessing using VectorAssembler
* Handling missing values
* Train-test split (80:20)

**Evaluation Metrics:**

* Accuracy
* Precision
* Recall
* F1 Score

**Visualization:**

* Confusion Matrix
* Age vs Fare Scatter Plot

---

### 🔹 2. Clustering (K-Means)

* Feature vector creation
* K-Means clustering (k = 3)

**Evaluation Metric:**

* Silhouette Score

**Visualization:**

* Cluster Scatter Plot (Fresh vs Milk)
* Elbow Method Graph

---

### 🔹 3. Recommendation System (ALS)

* Collaborative Filtering using ALS algorithm
* Train-test split performed on ratings data
* Implemented using both:

  * External movie ratings dataset
  * **Custom synthetic dataset using PySpark Rows (for better understanding)**

**Additional Implementation Details:**

* Created DataFrame using `Row()` objects
* Generated predictions using trained ALS model
* Converted Spark DataFrame to Pandas for visualization

**Evaluation Metric:**

* RMSE (Root Mean Square Error)

**Output:**

* Top-N movie recommendations per user
* Predicted ratings for user-item pairs

**Visualization:**

* Actual vs Predicted Ratings Scatter Plot
* Rating Distribution Histogram

---


### 🧠 Key Insight

* Demonstrates ALS working effectively even on **small-scale datasets**
* Helps in understanding **matrix factorization behavior before scaling to big data systems**

---

## 📊 Results

* ✔ Classification model achieved good prediction accuracy
* ✔ Clustering grouped customers into meaningful segments
* ✔ Recommendation system successfully predicted user preferences

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**
2. Install PySpark (if not already installed)
3. Run all cells sequentially
4. Ensure internet connection for dataset loading

---

## 📁 Project Structure

```
📦 BDA-Assignment
 ┣ 📜 BDA_ASSIGNMENT.ipynb
 ┣ 📜 README.md
```

---

## 🎯 Learning Outcomes

* Understanding of PySpark MLlib
* Implementation of machine learning models on big data
* Hands-on experience with distributed data processing
* Practical exposure to recommendation systems using ALS

---

## 📌 Conclusion

This project demonstrates the practical application of **classification, clustering, and recommendation techniques** using PySpark, providing a strong foundation in Big Data Analytics.

---

## 👨‍💻 Author

* **Name:** Deekshitha Chilla
* **Roll No:** 160123771076
* **Course:** Big Data Analytics
* **Institution:** Chaitanya Bharathi Institute of Technology
