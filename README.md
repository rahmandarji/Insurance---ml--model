# Insurance Cost Prediction using Machine Learning

This project predicts medical insurance charges based on personal and lifestyle factors using Machine Learning.

---

##  Problem Statement

The goal is to predict **insurance charges** based on features like:
- Age
- BMI
- Number of children
- Smoking status
- Sex
- Region

---

##  Dataset

The dataset contains patient information including:
- `age`
- `sex`
- `bmi`
- `children`
- `smoker`
- `region`
- `charges` (target variable)

---

##  Workflow

### 1. Data Cleaning
- Checked missing values
- Removed duplicates

### 2. Exploratory Data Analysis (EDA)
- Histograms for age and BMI
- Count plots for categorical features
- Correlation heatmap

### 3. Feature Engineering
- One-hot encoding using `pd.get_dummies()`

### 4. Preprocessing
- Converted boolean columns to integers
- Split dataset into training and testing sets (80/20)

### 5. Model Building
- Used **Random Forest Regressor**
- Trained on processed data

---

##  Evaluation Metrics

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Final Result:
- **R² Score: ~0.85**

---

##  Key Insights

- Smoking status is the most important factor affecting insurance charges
- BMI and age also significantly influence cost
- Region has minimal impact on predictions

---

##  Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Project Structure
---

##  Future Improvements
- Hyperparameter tuning
- Cross-validation
- Deploy as a web app

---

##  Author

i built it to practice my logic and apply my knowledge in code. it is an Machine Learning learning project focused on regression and feature engineering.
