# 🎓 **STUDENT PERFORMANCE PREDICTION**
---

## 📝 **PROJECT OVERVIEW**
This project leverages **Ensemble Learning** to predict student academic outcomes (**Pass/Fail**). By combining multiple machine learning models through a **Voting Classifier**, the system achieves higher accuracy and reliability than any single model alone.

---

## 🚀 **KEY FEATURES**
* 🛠️ **Comprehensive Preprocessing:** Automated handling of categorical encoding and numerical feature scaling.
* 🤖 **Multiple Model Comparison:** Evaluates and compares 5+ different algorithms.
* 🗳️ **Advanced Ensemble Strategy:** Implements **Hard and Soft Voting** to aggregate predictions.
* 📈 **Real-world Inference:** Includes a dedicated script to test and predict new student data.

---

## 📊 **DATASET FEATURES**
The model analyzes **10 key features** to determine the final result:

| Category | Features Included |
| :--- | :--- |
| **Academic** | Previous Scores, Study Hours, Attendance (%) |
| **Demographic** | Age, Gender, Parental Education |
| **Environment** | Internet Access, Extra Classes |
| **Personal** | Stress Levels |

---

## 🛠️ **MODELS IMPLEMENTED**
We compared and combined the following algorithms to find the best fit:
1. **`Logistic Regression`** (Baseline)
2. **`Decision Tree`**
3. **`Random Forest`** (Bagging Ensemble)
4. **`Support Vector Machine (SVM)`**
5. **`K-Nearest Neighbors (KNN)`**
6. **`Voting Classifier`** (Final Hybrid Model)

---

## ⚙️ **HOW IT WORKS**
1. **Data Loading:** Reads raw data from `student_performance.csv`.
2. **Encoding:** Converts text categories into numbers using `LabelEncoder`.
3. **Scaling:** Normalizes data ranges using `StandardScaler`.
4. **Voting Logic:** The individual models "vote" on the outcome. **Soft Voting** is used to average the probabilities for the most accurate result.

---

## 💻 **TECH STACK**
* **Language:** `Python`
* **Machine Learning:** `Scikit-Learn`
* **Data Manipulation:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`

---

## 📈 **PREDICTION OUTPUT**
The final model classifies students into two categories:
* ✅ **`PASS`**: Student is likely to succeed based on current metrics.
* ❌ **`FAIL`**: Student may require academic intervention or support.

---

### 📂 **Project Files**
* `Student_Performance_Prediction.ipynb` - Main project code.
* `student_performance.csv` - Dataset.
* `diagram.png` - Visual representation of the Voting Classifier logic.
