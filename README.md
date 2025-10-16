# 📊 Hotel Booking Linear Regression Analysis

### 💡 Overview  
This project analyzes factors that influence **hotel room prices** (Average Daily Rate - ADR) using **Linear Regression**.  
The goal was to identify which booking characteristics most affect price and to build a statistical model that accurately predicts ADR.  

The work includes **data cleaning, feature selection, correlation analysis, model fitting, and diagnostics** — all implemented in **RStudio**.

---

### ⚙️ Technologies Used  
`RStudio` · `Linear Regression` · `Statistical Modeling` · `AIC/BIC Selection` · `Box-Cox Transformation` · `Data Visualization` · `Excel/CSV Data Handling`

---

### 🧠 Project Highlights  
#### 🔹 Data Exploration & Cleaning  
- Imported raw booking data and removed missing or inconsistent records.  
- Encoded categorical variables such as meal type, room type, and country.  
- Analyzed key numerical features: lead time, adults, children, and nights stayed.  
- Detected and handled outliers affecting the ADR variable.  

#### 🔹 Model Development  
- Built a **multiple linear regression model** to predict ADR.  
- Tested variable significance using t-tests and adjusted R².  
- Added **interaction terms** and **dummy variables** for categorical effects.  
- Applied **stepwise regression (AIC/BIC)** to select the optimal subset of predictors.  

#### 🔹 Model Evaluation & Improvement  
- Checked regression assumptions: linearity, homoscedasticity, multicollinearity, and normality of residuals.  
- Applied **Box-Cox transformation** and **log transformations** to improve model fit.  
- Compared several models and selected the one with the **lowest AIC** and **highest adjusted R²**.  

---

### 📈 Key Insights  
- **Lead time**, **number of adults**, and **room type** were the strongest predictors of price.  
- Outliers and categorical imbalance initially reduced model accuracy.  
- After transformation and feature selection, the model explained **≈80% of ADR variation**.  
- Demonstrated the importance of data preprocessing and model diagnostics in regression analysis.  

---
