# Retail Intelligence: Analysing Sales Drivers and Predicting Product Demand

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.2%2B-orange.svg)](https://scikit-learn.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> **Final Capstone Project Report** submitted in fulfillment of the requirements for the Data Science & AI Training Program by the **India Data Research Academy (IDRA)**.

---

## 📌 Project Overview

In multi-channel retail environments, inefficient inventory allocation results in dual operational failures: excessive safety stock incurs capital holding costs and spoilage, whereas stockouts trigger direct revenue loss and customer defection. 

This project investigates the operational, promotional, and macroeconomic drivers of retail sales demand across different store tiers and product departments. Using supervised machine learning pipelines, we build and evaluate predictive models to forecast weekly sales demand ($) on unseen data, preventing data leakage and providing actionable inventory replenishment policies.

---

## 👥 Candidate & Academic Metadata

* **Candidate Name:** [Your Name]
* **Institute:** [Your Institute / University]
* **Institute Roll No.:** [Your Roll Number]
* **Enrollment No.:** IDRA-[Your Enrollment Number]
* **Program:** Data Science & AI Training Program (IDRA 2026)
* **Academic Supervisor:** Dr. Shaheena Salam

---

## 📂 Repository Structure

```text
├── README.md                                  <- Executive project summary & reproducibility guide
├── requirements.txt                           <- Core runtime dependencies
├── data/
│   ├── raw_retail_data.csv                    <- Unprocessed dataset (provided via LMS)[cite: 1]
│   └── cleaned_retail_data.csv                <- Cleaned, preprocessed dataset for modeling[cite: 1]
├── notebooks/
│   └── Surname_Name_Capstone_Notebook.ipynb   <- End-to-end reproducible Jupyter/Colab notebook[cite: 1]
├── reports/
│   └── Surname_Name_Capstone_2026.pdf         <- Final research-style PDF Capstone Report[cite: 1]
└── visuals/
    ├── fig1_sales_and_elasticity.png          <- Departmental sales & discount elasticity plots
    └── fig2_residuals_and_importance.png      <- Error distribution & MDI feature importance plots
