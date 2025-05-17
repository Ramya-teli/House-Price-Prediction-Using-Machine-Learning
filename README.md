# 🏠 House Price Prediction using Machine Learning

Predicting house prices is a crucial task in the real estate industry that helps stakeholders make informed decisions. In this project, we build a regression-based machine learning model in **Python** to predict the price of a house based on features like location, size, number of bedrooms, and more.

## 📊 Problem Statement

The goal is to build a predictive model using the **House Price Prediction Dataset**. The dataset contains 13 features describing properties. By training a model on this data, we can estimate house prices and gain insights into the housing market trends.

## 🧰 Libraries Used

- **Pandas** – Data manipulation and analysis  
- **Matplotlib** – Visualization  
- **Seaborn** – Advanced visualization (heatmaps, barplots)  
- **Scikit-learn** – Preprocessing, model training, and evaluation  

## ✅ Workflow

### 1. Data Loading and Inspection
- Load dataset using `pandas`
- Check structure and initial samples

### 2. Data Preprocessing
- Identify categorical, integer, and float variables
- Handle missing values
- Drop irrelevant columns like `Id`

### 3. Exploratory Data Analysis (EDA)
- Heatmap to show correlation between numeric features
- Barplots for unique categorical value counts
- Distribution analysis of key features

### 4. Data Cleaning
- Drop rows/columns with too many nulls
- Fill missing values with mean where necessary

### 5. Feature Encoding
- OneHotEncoding for categorical features using `OneHotEncoder`

### 6. Train-Test Split
- Use `train_test_split` (80/20 split) to divide data
                      

## 📈 Conclusion

- All three models performed reasonably well, with **Support Vector Regressor** and **Linear Regression** performing best.
- The model can now be used to estimate house prices based on new input data.

---

## 📁 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
