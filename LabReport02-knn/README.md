# 🌸 Iris Flower Classification using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This project implements **K-Nearest Neighbors (KNN)** classification on the **Iris Flower Dataset** using **scikit-learn**.  


The project includes:
- Data preprocessing
- Feature scaling
- Multiple train-test splits
- Model training with different k values
- Performance evaluation using standard classification metrics

---

## 📂 Dataset Information
- **Dataset Name:** Iris Flower Dataset


### Features
| Feature | Description |
|-------|------------|
| SepalLength | Sepal length in cm |
| SepalWidth | Sepal width in cm |
| PetalLength | Petal length in cm |
| PetalWidth | Petal width in cm |

---

## 🧹 Data Preprocessing

### 1️⃣ Missing Value Handling
- Checked for missing values
- Replaced missing values (if any) using **column mean**

### 2️⃣ Feature Scaling
- Applied **Min–Max Scaling** to normalize all numeric features  
- Scaling range: **[0, 1]**

### 3️⃣ Train-Test Split Ratios
The dataset was split using multiple ratios:
- **50:50**
- **60:40**
- **70:30**
- **80:20**

---

## 🤖 Model Used
- **Algorithm:** K-Nearest Neighbors (KNN)
- **Library:** scikit-learn
- **Distance Metric:** Euclidean (default)

### K Values Tested

---

## 📊 Model Evaluation Metrics
Each model configuration was evaluated using:

- **Accuracy**
- **Confusion Matrix**
- **Precision**
- **Recall**
- **F1-score**

Macro-averaging was used for multi-class evaluation.

---

## 🏆 Best Model Selection
The optimal model was selected based on **highest accuracy and balanced precision/recall**.

### ✅ Final Observation
- **Best Split Ratio:** 70:30 or 80:20  
- **Optimal K Value:** 3 or 5  
- **Achieved Accuracy:** ~96% – 100%

---


---

## 🛠 Technologies Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run the Project

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/iris-knn-classification.git

