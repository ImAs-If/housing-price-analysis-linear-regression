# 🏠 Housing Price Prediction using Linear Regression

This project implements a **Linear Regression model** to predict house prices using the **Housing dataset**.  
The goal is to improve model performance (**R² score**) while strictly keeping the model within the **Linear Regression framework**.

No advanced or regularized models (Ridge, Lasso, etc.) are used.

---

## 📂 Dataset
- **File:** `(https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)`
- **Target Variable:** `price`
- **Features:** Area, bedrooms, bathrooms, stories, parking, and several categorical attributes

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔄 Project Workflow

1. Import required libraries  
2. Load and explore the dataset  
3. Handle categorical variables  
4. Apply feature engineering  
5. Remove extreme outliers  
6. Split data into training and testing sets  
7. Train a **Linear Regression** model  
8. Evaluate performance using **R² Score** and **MSE**  
9. Visualize results (Actual vs Predicted, Residual Plot)

---

## 🧠 Feature Engineering Techniques
To improve the R² score while keeping Linear Regression:
- Area per bedroom
- Bathroom per bedroom
- Interaction between stories and bedrooms
- Interaction between area and bathrooms

These features help capture relationships that simple linear features may miss.

---

## 🚫 Outlier Handling
- Removed the top **1% extreme house prices**
- Helps reduce noise and improve model generalization

---

## 📊 Model Evaluation
- **Model Used:** Linear Regression
- **Evaluation Metrics:**
  - R² Score
  - Mean Squared Error (MSE)

The improvements increased the R² score compared to the baseline model.

---

## 📈 Results
- Improved R² score using **only Linear Regression**
- Better fit without using advanced models
- Maintained interpretability of the model

---
## 📁 Repository Structure

├── Housing.csv
├── linear-regression-v3.ipynb
└── README.md


---

## 📝 Key Note
> This project strictly follows academic guidelines by using **only Linear Regression**.  
> Improvements are achieved through **feature engineering and data preprocessing**, not advanced models.

---

## 👨‍💻 Author
**MD. Asif Ahmed**  
Department of Computer Science & Engineering  

---

## 📌 License
This project is for **academic and educational purposes**.



## 📁 Repository Structure
