# Diabetes Prediction Using Linear Regression 

## 📌 Project Overview
This project demonstrates a **machine learning pipeline** for predicting diabetes using the ** Diabetes Dataset**.  

---

## 📂 Dataset
- **File:** `diabetes.csv`
- **Records:** 768
- **Features:** 8 medical predictor variables
 

### Features Description
| Feature | Description |
|-------|------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure (mm Hg) |
| SkinThickness | Triceps skin fold thickness (mm) |
| Insulin | 2-Hour serum insulin (mu U/ml) |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes family history |
| Age | Age in years |

---

## 🧹 Data Preprocessing
1. **Zero Value Handling**  
   Zero values in the following features were replaced with the **column median**:
   - Glucose
   - BloodPressure
   - SkinThickness
   - Insulin
   - BMI

2. **Feature Modification**
   - First row’s glucose value replaced with **maximum glucose**
   - Records with **minimum age** had their glucose replaced with **minimum glucose**

3. **Feature Scaling**
   - Applied **StandardScaler** to normalize input features

---

## 🤖 Model Used
- **Algorithm:** Linear Regression  
- **Library:** `scikit-learn`
- Continuous predictions were:
  - Rounded (`np.rint`)
  - Clipped to binary values (0 or 1)



---

## 📊 Model Evaluation

### Metrics
- **Accuracy:** `0.7597`
- True Negatives: 83  
- False Positives: 16  
- False Negatives: 21  
- True Positives: 34  

---

## 📈 Visualization
- Confusion matrix visualized using **Seaborn Heatmap**
- Classification report printed using `classification_report`

---

## 🛠 Technologies Used
- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🚀 How to Run
1. Clone the repository
```bash
git clone https://github.com/your-username/diabetes-linear-regression.git

- **Precision:** `0.68`
- **Recall:** `0.6182`
- **F1-score:** `0.6476`



