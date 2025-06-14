<h1 align="center">#🏥 Medical Insurance Cost Prediction</h1>

<div align= "center">
  <h4>Smarter Health Choices: Forecasting Your Insurance Expenses with Machine Learning</h4><br>
  <img src="https://www.picpedia.org/clipboard/images/medical-insurance.jpg" style="width: 500px; height: 400px;">
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

---

## 📌 Overview

Medical insurance is a safety net that protects individuals and families from high healthcare expenses. However, the cost of insurance premiums can vary significantly based on personal and medical factors. This project uses machine learning to predict annual insurance premiums and helps users understand what factors influence those costs.

The aim is to empower individuals with better decision-making tools for health and financial planning.

---

## 🎯 Objective

The goal is to develop a machine learning model that predicts the yearly insurance premium of a customer based on:

- Demographic information
- Health indicators
- Lifestyle choices

This model can assist both individuals and insurers in understanding risk and cost factors transparently.

---

## 📊 Dataset

The dataset used is publicly available on Kaggle and contains health-related attributes of 1,000+ individuals:

**Features:**

- `age`: Age of the person
- `sex`: Gender
- `bmi`: Body Mass Index
- `children`: Number of dependents
- `smoker`: Smoking status (yes/no)
- `region`: Residential region
- `charges`: Yearly medical insurance premium (target variable)

📎 [Dataset Link](https://www.kaggle.com/datasets/tejashvi14/medical-insurance-premium-prediction)

---

## ⚙️ Methodology

### Step-by-step Process:

1. **Data Cleaning**
   - Null checks and consistency validation
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Visualizations (histograms, boxplots, pair plots)
   - Correlation heatmaps

3. **Feature Engineering**
   - One-hot encoding for categorical data
   - Outlier detection in BMI and charges

4. **Model Building**
   - Regression models: Linear Regression, Random Forest, Decision Tree
   - Hyperparameter tuning with GridSearchCV

5. **Evaluation**
   - Metrics: R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

---

## 🧠 Technologies Used

- Python 3.12+
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Joblib (for model saving)
- Flask (optional: for frontend API)

---

## 📝 Results

- **Best Model:** Random Forest Regressor
- **R² Score:** ~0.79
- **MAE:** ₹3,200
- **Important Features:**
  - Smoking status (most influential)
  - Age
  - BMI

---

## 💡 Bonus: Optional Web Interface

An optional Flask app can be built to allow users to input their details and get real-time predictions from the trained model.

You can enhance the interface using:

- HTML/CSS
- Bootstrap
- JavaScript for dynamic interaction

---

## 🚀 Future Improvements

- Use a larger, real-world dataset
- Integrate more health-related parameters (e.g., exercise level, medical history)
- Deploy with Docker or Streamlit
- Visualize SHAP values for model explainability

---

## 🤝 Contribution & License

This is a personal project made for learning and demonstration purposes. You’re free to use it, but please do not copy this exact README or model for academic cheating or unethical use.

---

## 📬 Contact

**Developers:** Ali Ahmad (Software Engineer) & Amina Maqsood (Software Engineer)  

**GitHub:** [Ali Ahmad](https://github.com/AliAhmad238)  
**Email:** mattarii78@gmail.com

---
