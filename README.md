# Medical Insurance Cost Prediction System
![](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRH3VLS5TaEI2RWKJgQtrmuXQBjWPQ3rlfh_w&s)

## 📝 Overview
This repository contains a complete end-to-end Machine Learning predictive system designed to estimate medical insurance costs for individuals. Built using Python and the `Scikit-Learn` library, the core of this system relies on a **Linear Regression** model. 

The project takes foundational health and demographic data—such as age, BMI, family size, and lifestyle choices (smoking habits)—and maps them to historical insurance charges. To make the model practical for real-world use, the system includes a dedicated, reusable prediction pipeline function that allows users to instantly input new patient data and receive real-time cost estimations without retraining the model.

---

## 🎯 Project Objectives
The primary goals of this project are:
* **Accurate Cost Estimation:** To develop a robust regression model capable of predicting individual medical insurance premiums with minimal error based on historical data.
* **Feature Impact Analysis:** To analyze and quantify how strongly different factors (especially lifestyle choices like smoking vs. physical metrics like BMI) influence overall insurance pricing.
* **Reusable Pipeline Engineering:** To build a clean, production-ready Python function (`get_insurance_cost`) that handles data formatting, array reshaping, and inference automatically.
* **Data Preprocessing & Cleaning:** To implement clean data pipelines for handling categorical variables (e.g., encoding `sex`, `smoker`, and `region` into numerical formats) and addressing linear regression assumptions.
