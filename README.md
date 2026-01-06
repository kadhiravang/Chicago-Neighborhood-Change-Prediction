# 🏙️ Predicting Neighborhood Change in Chicago Using Machine Learning

**Course:** CSP 579 – Online Social Network Analysis  
**Instructor:** Prof. Cynthia Hood  
**Institution:** Illinois Institute of Technology  

This project integrates open U.S. Census data and machine learning models to predict neighborhood-level socioeconomic change across Chicago’s block groups from 2010 to 2025.

---

## 🔍 Overview
- Combined ACS (2015–2025) and Decennial Census (2010) data.
- Engineered socioeconomic indicators: median income, education, renter share, poverty.
- Applied **Multinomial Logistic Regression** and **Random Forest Classifier**.
- Validated spatial structure using **Moran’s I** and **Louvain community detection**.

---

## 🧠 Tools & Libraries
R | tidycensus | sf | dplyr | ggplot2 | caret | randomForest | spdep | igraph

---

## 📊 Results
- Education and renter share were the strongest predictors of growth.
- Spatial autocorrelation confirmed neighborhood transitions are geographically structured.
- Achieved ~78% model accuracy with consistent cross-validation performance.

---

## 🚀 Future Work
- Integrate real-estate and mobility data for richer features.
- Extend forecasts to 2030 using time-series analysis.
- Develop an interactive dashboard for visualization.

---

## 📚 Reference
> “Predicting Neighborhood Change Using Publicly Available Data and Machine Learning,” SSRN Electronic Journal, 2021.  
> ChatGPT was used for code documentation and formatting support.

---

## 👤 Author
**Kadhiravan Gopal**  
M.S. in Artificial Intelligence 
Illinois Institute of Technology  
