#  Zomato Analysis & Bulldozer Price Prediction

##  Overview
This repository features two end-to-end data science projects completed as part of my coursework and self-learning:

- **Zomato Mini-Assignment** – Focused on cleaning, analyzing, and visualizing restaurant data from the Zomato dataset.
- **Bulldozer Price Prediction** – Built a machine learning model to predict the sale prices of bulldozers at auctions using historical data.

These projects demonstrate key skills in data preprocessing, feature engineering, exploratory data analysis (EDA), and machine learning modeling using Python.

---

##  Zomato Mini-Assignment

###  Key Steps:
- Loaded and explored raw restaurant data.
- Handled missing values and standardized important columns.
- Extracted **primary cuisine** for each restaurant entry.
- Grouped data by cuisine to compute:
  - Average rating  
  - Total votes  
  - Average cost for two
- Created simple yet insightful visualizations:
  - Top cuisines by average rating  
  - Most popular cuisines by vote count

###  Files:
- `zomato_analysis.ipynb`: Main notebook with step-by-step analysis.
- `cleaned_zomato.csv`: Cleaned dataset after preprocessing.
- `cuisine_summary.csv`: Summary statistics grouped by cuisine.

---

## Bulldozer Price Prediction

### Key Steps:
- Cleaned and preprocessed auction data (handled missing values, fixed data types).
- Parsed `saledate` to extract features like year, month, and day.
- Encoded categorical features.
- Trained a **Random Forest Regressor** for price prediction.
- Achieved a validation **RMSLE of 0.2154**.
- Generated predictions for the test set in the required format.

### Files:
- `bulldozer_prediction.ipynb`: Full notebook with preprocessing, training, and evaluation.
- `test_predictions.csv`: Final predictions on the test data.

---

##  Tools & Technologies Used
- **Languages**: Python  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `scikit-learn`  
- **Platform**: Google Colab  
- **Version Control**: Git & GitHub

---

##  Notes
These projects were part of my hands-on learning journey into data science and machine learning. All work is original, and I focused on applying practical techniques to real-world datasets.
