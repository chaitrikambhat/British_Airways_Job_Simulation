# British Airways Data Science Simulation – Forage

This repository contains my end-to-end solution for the **British Airways Data Science Virtual Experience Program** on [Forage](https://www.theforage.com/). The project simulates a real-world business scenario where data science is used to enhance customer experience and booking behavior prediction.

---

## 📌 Objective

Use historical flight and customer data to:
- Explore key factors affecting booking behavior
- Engineer meaningful features to enrich the dataset
- Build a predictive model to estimate the likelihood of a customer completing a booking

---

## 📊 Key Steps

- **Feature Engineering**: Extracted flight timing patterns (e.g., weekend vs. weekday, time of day), and ratio-based features to capture customer intent.
- **Model Training**: Used a Random Forest classifier to predict booking completion with strong performance.
- **Evaluation**:
  - Achieved **ROC AUC Score of ~0.85**
  - Performed 5-fold cross-validation to validate model stability
  - Visualized feature importances to explain key drivers

---

## 🔧 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebooks
- Forage (Simulation environment and dataset)

---

## 📁 Note on Data

> The dataset `customer_booking.csv` used in this project was provided exclusively as part of the Forage simulation. It is **not included in this repository** due to licensing restrictions. You can access the dataset directly by enrolling in the British Airways experience on Forage.

---

## 📌 Sample Output

- Confusion matrix and ROC AUC evaluation
- Feature importance bar chart
- `top_features.csv` summarizing most predictive variables

---

## 🙋‍♂️ About Me
  
Feel free to connect or reach out:
- [LinkedIn](https://www.linkedin.com/in/chaitrika-m-bhat/)
- [Email](chaitrikambhat@gmail.com)
