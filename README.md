<div align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-Learn Badge"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter Badge"/>
  <img src="https://img.shields.io/badge/Machine%20Learning-e11d48?style=for-the-badge&logo=ai&logoColor=white" alt="ML Badge"/>
</div>

<br>

# 🛒 Supermart Grocery Regression Analytics

> **Transforming a 10,000-row categorical retail database into a robust predictive Linear Regression Machine Learning model.**

## 📖 Project Overview
Retail inventory control often suffers due to a lack of accurate revenue estimation across disparate regional stores. This project ingests nearly 10,000 individual transactional records tracking geographical zones, sub-categories, and grocery items.

The primary objective is to execute a rigorous sequence of **data type encoding** and **multivariate linear regression**, establishing baseline mathematical dependencies to accurately predict final gross `Sales` (USD) derived entirely from contextual and categorical labels constraint points.

---

## 🚀 Key Technical Achievements
- **Label Encoding Transformation**: Successfully solved "The Alphabet Problem" (where ML models cannot parse text) by utilizing `LabelEncoder()` to map unstructured string categories (`City`, `Region`, `Item Type`) into uniform numeric structures without discarding feature relationships.
- **Categorical Linear Regression Pipeline**: Engineered an active Ordinary Least Squares (OLS) hyperplane via Scikit-Learn that evaluates the numeric weights natively, predicting forward financial outcomes with high statistical validity.
- **R-Squared Superiority**: The model achieved an exceptional **R² score of 0.82**, demonstrating that 82% of all final gross revenue variance is mathematically explainable merely from the categorical metadata. 
- **Geographic Anomaly Detection**: Proved that revenue output completely defied general regional population density assumptions. The data pipeline isolated *Kanyakumari* ($70K+) operating with substantially higher throughput than primary metropolitan centers like *Chennai*.

---

## 📁 Repository Structure
```text
├── 📄 Task4_Supermart_Grocery_Sales_Analysis.ipynb    # Primary NLP & Regression Notebook
├── 📄 GrocerySalesReport.pdf                          # Executive Level Final Slide Deck
├── 📄 Supermart Grocery Sales Dataset.pdf             # Detailed Walkthrough Document
├── 📄 Task4_Supermart_Grocery_PPT.html                # Interactive Web Presentation
└── 📄 Supermart_Grocery_Sales.csv                     # Raw Source Database
```

## 🛠️ Tech Stack & Methods
* **Language:** Python
* **Machine Learning & Preprocessing:** `scikit-learn` (LinearRegression, LabelEncoder, R2_Score, mean_squared_error)
* **Data Handling:** `pandas`, `numpy`
* **Geospatial & Category Visuals:** `matplotlib`, `seaborn`

## 💵 Strategic Value
With a verified testing architecture displaying a highly compressed Actual vs. Predicted scatter vector (approaching the absolute 1:1 diagonal), this `.pkl` object can be exported and attached natively to Supermart's backend infrastructure. It converts historical invoicing categories dynamically into automated, probabilistic future-yield estimations.

## ⚙️ How to Run
1. Clone the repository locally.
2. Initialize strict virtual environment dependencies:
   `pip install pandas==2.1.0 numpy==1.25.0 scikit-learn==1.3.0 matplotlib==3.7.0 seaborn==0.12.0`
3. Execute the Jupyter notebook chronologically.

---
*Authored by Finance Analyst as a Demonstration of Advanced Market Modeling.*
