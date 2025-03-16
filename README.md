# 🚬 Breaking the Habit: Predicting Smoking Patterns Through AI

## 📌 Project Overview
This project aims to predict smoking history using health data with the help of **machine learning models**. Traditional methods rely on self-reported smoking habits, which can be inaccurate. By leveraging health indicators such as **lung capacity, biomarkers, and physiological parameters**, this approach improves early detection and facilitates **personalized healthcare interventions**.

## 🏆 Motivation
Predicting smoking behavior accurately is crucial in **preventive healthcare**. By utilizing AI-driven insights, we can:
- Reduce reliance on self-reported smoking data.
- Detect smoking-related risks early.
- Improve personalized interventions and healthcare outcomes.

## ⚙️ Preprocessing Pipeline
A **clean and balanced dataset** is essential for reliable model performance. The following steps were implemented:

1. **Data Cleaning**: 
   - Removed duplicate rows.
   - Handled missing values.
   - Encoded categorical features (`sex`, `DRK_YN`).

2. **Standardization**:
   - Scaled numerical features (e.g., `age`, `height`, `weight`, `blood metrics`) to improve model performance.

3. **Class Balancing**:
   - Used **undersampling techniques** to balance smoker and non-smoker representation.

4. **Data Splitting**:
   - **70% Training** | **30% Testing** to ensure robust model evaluation.

---

## 📊 Models and Results

### ✅ **1. Gradient Boosting Classifier (GBC)**
- 📌 **Description**: Uses sequential decision trees to minimize errors over multiple iterations.
- 🏆 **Performance Metrics**:
  - **Accuracy**: 82.98%
  - **F1-Score**: 0.819
- ✅ **Strengths**: Excellent at handling complex feature relationships.
- ❌ **Limitations**: Computationally expensive; may overfit small datasets.

---

### ✅ **2. Linear Support Vector Machine (SVM)**
- 📌 **Description**: A linear classifier that separates data using hyperplanes.
- 🏆 **Performance Metrics**:
  - **Accuracy**: 82.63%
  - **F1-Score**: 0.822
- ✅ **Strengths**: Efficient for high-dimensional data and interpretable.
- ❌ **Limitations**: Struggles with **non-linear** relationships.

---

### ✅ **3. Random Forest Classifier**
- 📌 **Description**: A bagging algorithm using multiple decision trees for robustness.
- 🏆 **Performance Metrics**:
  - **Accuracy**: 82.98%
  - **F1-Score**: 0.830
- ✅ **Strengths**: Handles categorical and continuous features well.
- ❌ **Limitations**: Requires more computational resources.

---

## 📈 Benchmark and Analysis
- **Best Model**: **Random Forest** and **Gradient Boosting** achieved the **highest accuracy (82.98%)** and competitive **F1-scores**.
- **Comparison**: 
  - Linear SVM is efficient but struggled with complex feature interactions.
  - Random Forest and Gradient Boosting provided **better predictive performance**.
- **Trade-offs**:
  - **Gradient Boosting** is **resource-intensive**.
  - **Random Forest** offers **better scalability and interpretability**.

---

## 🔮 Conclusion
This project highlights the potential of **machine learning in healthcare** by predicting smoking behavior through **health indicators**. The best models—**Random Forest and Gradient Boosting**—demonstrated high accuracy and robustness. 

🔹 **Future Work**:
- **Ensemble learning**: Combining multiple models for better prediction.
- **Feature engineering**: Exploring more **biomarkers and health indicators**.
- **Expanding dataset**: Using more diverse populations for improved generalization.

---

## 🛠 Tech Stack
- **Programming Language**: Python 🐍
- **Libraries**:
  - `pandas` `numpy` `scikit-learn` `tensorflow`
  - `seaborn` `matplotlib` `imbalanced-learn`

---

## 📂 Repository Structure
