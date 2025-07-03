# Olmypics_data_analysis
# 🏅 Olympics Medal Prediction Using Random Forest

## 📖 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Workflow](#project-workflow)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation & Usage](#installation--usage)
- [Results](#results)
- [Visualizations](#visualizations)
- [Key Insights](#key-insights)
- [Limitations & Future Work](#limitations--future-work)


---

## Project Overview

This project leverages machine learning to predict **which Olympic medal (Gold, Silver, Bronze, or None) an athlete is likely to win** based on their personal and event information. Using a Random Forest classifier, the project not only achieves medal prediction but also identifies the most influential factors contributing to Olympic success.

---

## Dataset

- **Source:** [Kaggle - 120 years of Olympic history: athletes and results](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
- **File Used:** `athlete_events.csv`
- **Attributes:**
  - Athlete demographics (Age, Sex, Height, Weight)
  - Event details (Sport, Event, Season, Year)
  - Country (NOC)
  - Medal won (Gold, Silver, Bronze, or None)

---

## Project Workflow

1. **Data Loading & Exploration**
   - Load the dataset and perform exploratory data analysis (EDA).
   - Visualize missing values, medal distribution, and country participation.

2. **Data Preprocessing**
   - Handle missing values with appropriate strategies (e.g., median imputation).
   - Encode categorical variables (Label Encoding and One-Hot Encoding).
   - Feature scaling using StandardScaler.

3. **Feature Selection**
   - Use Random Forest feature importances to select the most relevant features.

4. **Model Training**
   - Train a Random Forest classifier on the processed data.

5. **Prediction & Evaluation**
   - Predict medal outcomes for test data.
   - Evaluate model performance using accuracy, classification report, and confusion matrix.

6. **Interpretation & Visualization**
   - Plot feature importances to understand the key drivers of medal success.

---

## Features

- Predicts specific medal outcome (Gold, Silver, Bronze, None) for each athlete.
- Identifies and visualizes the most important features influencing medal wins.
- Handles missing data and categorical variables efficiently.
- Provides clear visualizations for data understanding and model interpretation.

---

## Technologies Used

- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, scikit-learn, Matplotlib, Seaborn

---


---

## Visualizations

- **Medal Distribution Bar Chart**
- **Missing Values Heatmap**
- **Country Participation Bar Chart**
- **Feature Importance Plot**

<!-- You can add screenshots or sample plots here if available -->

---

## Key Insights

- The most important factors influencing medal wins include:
- (List your top features, e.g., Country (NOC), Sport, Age, etc.)
- There is a class imbalance, with most athletes not winning any medal.
- Certain countries and sports have higher medal-winning probabilities.

---

## Limitations & Future Work

- **Limitations:**
- Class imbalance may affect prediction performance for rare medal types.
- Model does not account for recent changes in sports or athlete performance trends.

- **Future Improvements:**
- Experiment with other machine learning algorithms (e.g., XGBoost, SVM).
- Incorporate additional features such as team events or athlete experience.





- **Hemant Joshi**
- **Email:** hemant.ai@bmsce.ac.in




