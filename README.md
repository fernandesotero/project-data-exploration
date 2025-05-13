# 🎓 Student Performance Prediction with Data Science

This project aims to apply data science techniques to predict **students academic performance** based on their study habits, lifestyle, and socioeconomic background. The main idea is to explore how different behavioral and contextual variables influence final exam scores using machine learning.

## 📁 Dataset

The dataset used, named `student_habits_performance.csv`, contains **1,000 student records** with the following information:

- Demographic data (age, gender)  
- Daily habits (study hours, sleep, social media, Netflix)  
- External conditions (part-time job, internet quality, parents' education level)  
- Health and well-being (exercise, diet, mental health)  
- Participation in extracurricular activities  
- Final exam score (target variable: `exam_score`)

## 🎯 Objective

To develop a predictive model capable of estimating a student's exam score based on their habits and characteristics, enabling:

- Understanding of the variables that most impact academic performance  
- Support for the development of data-driven educational policies  
- Practical demonstration of machine learning techniques

## ⚙️ Project Steps

### 1. Exploratory Data Analysis (EDA)

Tools used: `pandas`, `seaborn`, `matplotlib`

- Check data types, missing values, and descriptive statistics  
- Graphical analysis of distributions, correlations, and variable relationships  
- Initial understanding of data patterns

### 2. Preprocessing

Tools used: `scikit-learn` (`ColumnTransformer`, `StandardScaler`, `OneHotEncoder`)

- Separation of numerical and categorical features  
- Normalization of continuous variables  
- Encoding of categorical variables (one-hot encoding)  
- Removal of irrelevant columns (e.g., student ID)

### 3. Predictive Modeling

Models used:
- **Linear Regression** – Baseline model to evaluate simple linear relationships  
- **Random Forest Regressor** – Robust, non-linear model to capture complex interactions

Both models were integrated into a `Pipeline`, enabling automatic execution of preprocessing and training.

### 4. Evaluation

Metrics used:
- **R² (coefficient of determination)**: measures explained variance  
- **MAE (Mean Absolute Error)**: interprets average error in actual units  

These metrics allow for model comparison and understanding of prediction effectiveness.

## 🧠 Conclusion

The project demonstrated how behavioral and lifestyle data can be analyzed to predict academic performance. In addition to building predictive models, it helped identify key factors that influence students' learning—valuable insights for real-world educational applications.

## 🛠️ Technologies and Libraries

- Python  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn

## 📌 Future Improvements

- Hyperparameter tuning with GridSearchCV  
- Testing other models (XGBoost, LightGBM)  
- Feature selection to reduce complexity  
