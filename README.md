# Customer Lifetime Value (LTV) Prediction  

This project focuses on analyzing and predicting Customer Lifetime Value (LTV) using machine learning models. The goal is to explore patterns in LTV and build a highly accurate predictive model.  

## 📌 Project Overview  
### 🔹 Data Processing  
- Encoded categorical variables.  
- Scaled numerical features.  
- Checked for missing values (none found).  

### 🔹 Exploratory Data Analysis (EDA)  
- Top 10 customers with the highest LTV.  
- LTV categorization: Grouped into Low, Medium, High, and Very High categories.  
- LTV distribution across categories.  
- Heatmap analysis of customer attributes and LTV.  
- Customer Satisfaction vs. LTV  
- Average LTV vs Payment Method.  

### 🔹 Model Training & Evaluation  
- Implemented Random Forest, XGBoost, and LightGBM.  
- Evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and R² Score.  
- Final Results:  
  - R² Score ≈ 0.99 (indicating strong predictions).  
  - MSE and MAE were minimal, confirming accuracy.  
  - Actual vs. Predicted LTV values were nearly identical.  

## 🔧 Tech Stack  
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn)  
- Machine Learning Models: Random Forest, XGBoost, LightGBM  
- Jupyter Notebook (VS Code)  

## 🚀 How to Use  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/LTV-Prediction.git
