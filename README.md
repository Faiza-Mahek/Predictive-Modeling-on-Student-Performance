# Predictive Modeling on Student Performance

**Assigned On:** 07 Jan 2025 at 23:08:53  
**Due Date:** 14 Jan 2025  
**Status:** Complete

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Tools & Technologies](#tools--technologies)  
4. [Implementation Steps](#implementation-steps)  
5. [Presentation](#presentation)  
6. [References](#references)

---

## Project Overview

In this task, we build a predictive model using a supervised learning approach on the **Student Performance** dataset. The focus is on predicting a student’s math score based on various factors such as:

- Gender  
- Race/Ethnicity  
- Parental Level of Education  
- Lunch Type  
- Test Preparation Course  

We explore algorithms like **decision trees**, **logistic regression**, and **random forests**, then evaluate them using metrics such as **accuracy**, **precision**, **recall**, and **F1 score**.

---

## Dataset

- **Name:** Student Performance in Exams  
- **Source:** [Kaggle: Student Performance Dataset](https://www.kaggle.com/spscientist/students-performance-in-exams)  
- **Description:** Provides demographic information and test scores (math, reading, writing) for students, enabling predictive modeling on academic performance.

---

## Tools & Technologies

- **Python (3.x)**  
- **Jupyter Notebook**  
- **Machine Learning Libraries**: scikit-learn, Pandas, NumPy, Matplotlib, Seaborn, etc.  
- **Feature Selection Techniques**: e.g., chi-square, feature importance in tree-based models, correlation analysis

---

## Implementation Steps

1. **Data Loading**  
   - Download the dataset from [Kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams).  
   - Load into a Pandas DataFrame.

2. **Data Exploration & Cleaning**  
   - Inspect dataset shape, data types, and any missing values.  
   - Clean or transform categorical features (e.g., label encoding, one-hot encoding).

3. **Feature Engineering**  
   - Create or modify features if beneficial (e.g., combining categories, normalizing numeric data).  
   - Split data into training and test sets.

4. **Model Training**  
   - Train multiple models: **Decision Tree**, **Logistic Regression**, **Random Forest**, etc.  
   - Adjust hyperparameters as needed (e.g., GridSearchCV).

5. **Evaluation**  
   - Compute metrics: Accuracy, Precision, Recall, F1 Score.  
   - Compare models and select the best-performing approach.

6. **Feature Selection**  
   - Assess feature importance (e.g., using Random Forest’s feature_importances_).  
   - Explore correlation-based removal or domain-driven elimination of irrelevant attributes.

7. **Conclusion**  
   - Summarize which model performed best and discuss how feature selection impacted results.

---

## Presentation

### PPT Link
> **[Click Here to View the Presentation Slides](https://www.canva.com/design/DAGZkZWrXv8/afX0_FZBCKRUfkkrk5dobA/edit)**

*(Replace the above link with your actual presentation URL once available.)*

---

## References

- **Student Performance Dataset:** [Kaggle - spscientist/students-performance-in-exams](https://www.kaggle.com/spscientist/students-performance-in-exams)  
- **Scikit-learn Documentation:** [scikit-learn.org](https://scikit-learn.org/)  
- **Pandas Documentation:** [pandas.pydata.org](https://pandas.pydata.org/)  
