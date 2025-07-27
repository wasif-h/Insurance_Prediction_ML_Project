
# 🏥 Insurance Prediction - ML Project


## 📊 Dataset Overview

**Features:**

- `age` – Age of the individual
- `sex` – Gender (`male`, `female`)
- `bmi` – Body Mass Index
- `children` – Number of children
- `smoker` – Smoking status (`yes`, `no`)
- `region` – Residential region in the US (`northeast`, `northwest`, `southeast`, `southwest`)
- `charges` – Individual medical costs billed by health insurance

---

## ✅ Project Workflow

The major steps of this project include:

1. **Exploratory Data Analysis (EDA)**  
   - Univariate & bivariate analysis  
   - Statistical summaries & distributions  

2. **Data Visualization**  
   - Histograms, scatter plots, box plots, pair plots  
   - Heatmaps to examine correlation  

3. **Feature Engineering**  
   - Encoding categorical variables (`sex`, `smoker`, `region`)  
   - Handling multicollinearity and outliers  
   - Creating dummy variables for regions  

4. **Data Preprocessing**  
   - Missing value check  
   - Feature scaling (if needed)  
   - Train-test split  

5. **Modeling**  
   - Applied **Linear Regression**  
   - Evaluated model with R², MAE, MSE  

6. **Prediction**  
   - Predicted `charges` based on the trained model  

---

## 📁 Folder Structure

```

Insurance\_Prediction\_ML\_Project/
│
├── data/               # Dataset (if available)
├── notebooks/          # Jupyter notebooks for EDA, modeling
├── images/             # Plots & visualizations
├── models/             # Saved model files (if any)
├── README.md           # Project overview
└── requirements.txt    # Dependencies

````
