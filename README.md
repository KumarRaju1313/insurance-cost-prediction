# 💸 Insurance Charges Prediction

This project predicts individual medical insurance charges based on demographic and lifestyle factors using machine learning regression models.

---

## 📁 Dataset

The dataset includes the following features:

- `age` — Age of the policyholder  
- `sex` — Gender  
- `bmi` — Body Mass Index  
- `children` — Number of dependents  
- `smoker` — Smoker status  
- `region` — Residential region  
- `charges` — Target variable (Insurance premium)

The dataset is available in the `data/` directory.

---

## 📊 Methodology

### 🧪 Data Exploration
- View summary statistics and unique categorical values.
- Visualize distributions of key variables like age, BMI, and charges.

### 🧼 Data Preprocessing
- Handle missing values (if any).
- Encode categorical variables using one-hot encoding.
- Standardize numerical columns for uniformity.

### 🤖 Model Training
Train the following regression models:
- K-Nearest Neighbors (KNN)  
- Linear Regression  
- Support Vector Machine (SVM)  
- Decision Tree Regressor  
- Random Forest Regressor

### 📏 Model Evaluation
- Metric: **Mean Absolute Error (MAE)** on the test set.

---

## 📈 Results

| Model               | MAE        |
|---------------------|------------|
| KNN                 | 3532.65    |
| Linear Regression   | 4243.65    |
| SVM                 | 8478.46    |
| Decision Tree       | 2817.28    |
| Random Forest       | **2575.89** ✅ |

---

## 🔍 Conclusion

- The **Random Forest Regressor** outperformed all other models with the lowest Mean Absolute Error of **2575.89**.
- Simpler models like Linear Regression and SVM were less effective for this dataset.
- Proper preprocessing (like encoding and scaling) had a significant impact on overall model performance.

---

## ⚙️ Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook
