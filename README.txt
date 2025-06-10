# Multiple Linear Regression: A Case Study on Insurance Redlining

This project investigates the relationship between racial composition and insurance coverage patterns in Chicago ZIP codes from 1977–78. Using a multiple linear regression model, the study explores how race and other socio-economic factors impact the issuance of FAIR insurance policies.

---

## 📊 Dataset
The data were collected by the U.S. Commission on Civil Rights and include:
- **involact**: FAIR policies issued per 100 housing units (response)
- **race**: % minority population
- **fire**: fires per 100 housing units
- **theft**: thefts per 1,000 residents
- **age**: % homes built before 1939
- **income**: median family income (log-transformed)

---

## 🔍 Methods
- Exploratory Data Analysis (EDA)
- Variable screening and selection
- Multicollinearity diagnostics
- Model validation (PRESS, LOOCV)
- Residual diagnostics and outlier detection

---

## 📈 Results
The final model retained:
- `race`, `fire`, `theft`, and `age`  
- `income` was excluded based on selection criteria and multicollinearity

Findings show a **positive association between minority percentage and FAIR policy issuance**, raising questions about potential systemic disparities.

---

## 📎 Full Report (RPubs)
📖 [Click here to view the interactive R Markdown report on RPubs](https://rpubs.com/lukahere007/redlining-regression-chicago)  
_(Replace with your actual link)_

---

## 🗂️ Files
- `Mutlti-Linear-Regression_Redlining.Rmd` – full R Markdown source
- `Mutlti-Linear-Regression_Redlining.html` – rendered HTML report
- `README.md` – this summary

---

## 📌 Author
**Luke Wamalwa**  
Master’s Candidate, Applied Statistics & Data Science  
University of Kansas Medical Center

