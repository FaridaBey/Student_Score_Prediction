# Student_Score_Prediction

This project aims to predict students’ exam scores based on various academic and behavioral features. It applies machine learning techniques to analyze correlations between factors like attendance, study hours, previous scores, and tutoring, and evaluates different regression models.

---

## 📌 Project Overview
The project explores how different student-related factors influence exam performance.  
Key steps:
- Data preprocessing (cleaning, handling nulls, encoding if needed)
- Exploratory Data Analysis (EDA) with correlations & visualizations
- Feature selection based on correlation with `Exam_Score`
- Model training and evaluation:
  - Linear Regression
  - Polynomial Regression (performance comparison)
- Performance evaluation using metrics such as:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score

---

## 📂 Project Structure
```
Student_Score_Prediction.ipynb   # Main notebook with code and analysis
README.md                        # Project documentation
```

---

## 🚀 Requirements
To run this project, install the following dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## ▶️ How to Run
1. Clone this repository or download the notebook.
2. Install the dependencies listed above.
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Student_Score_Prediction.ipynb
   ```
4. Run the cells step by step to see preprocessing, EDA, and model training results.

---

## 📊 Results
- Features most correlated with exam scores: **Attendance, Hours_Studied, Previous_Scores, Tutoring**  
- Linear regression provides a baseline.  
- Polynomial regression improves performance by capturing nonlinear relationships.  



