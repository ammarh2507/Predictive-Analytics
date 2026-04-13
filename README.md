# Supply Chain Predictive Analytics: Consulting Case Studies

## Project Overview
This repository contains data analytics and machine learning project developed as part of a simulated consulting engagement for the "Brooklyn Group for Consulting" (BGC). The objective was to apply predictive modeling and data analysis to solve diverse, real-world supply chain and business operations challenges.

## Repository Structure
* **`PROJECT WORK FILE - Final.ipynb`**: The main Jupyter Notebook containing the code, exploratory data analysis (EDA), and predictive models for all three case studies.
* **`Confusion Matrix.ipynb`**: A dedicated notebook evaluating the classification model's performance for the predictive maintenance case study.
* **`Project.pdf`**: The final project report and presentation of findings.
* *(Note: The datasets `Rides_daily.csv`, `predictive_maintenance.csv` (train/test), and `auction_data.csv` are omitted from this public repository for academic integrity.)*

## Skills & Technologies
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Key Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Techniques:** Exploratory Data Analysis (EDA), OLS Regression, LASSO Regression, Decision Trees, Random Forests, Classification Modeling, Monte Carlo Simulation.

---

## Case Studies Included

### 1. Urban Mobility Demand Forecasting (Citi Bike, NYC)
* **Objective:** Identify factors influencing the number of daily rides for NYC's Citi Bike service to optimize fleet allocation.
* **Data Context:** Daily ridership metrics matched with calendar and environmental variables.
* **Methods:** * Conducted Exploratory Data Analysis (EDA) and correlation assessments.
  * Built and evaluated OLS Regression models to predict daily ridership based on weather and calendar variables.
  * Applied LASSO Regression for feature selection.
  * Developed Regression Trees and Random Forest models to determine non-linear feature importance.

### 2. Predictive Maintenance for Manufacturing Quality Assurance
* **Objective:** Develop a classification model using production process characteristics to predict faulty manufacturing parts, reducing waste and improving quality assurance.
* **Data Context:** Train and test datasets containing temperature, operational timing, and machine performance metrics.
* **Methods:**
  * Processed production data to identify patterns leading to equipment failure.
  * Built a classification model and evaluated performance using Accuracy, Precision, Recall, and Confusion Matrices to ensure a robust true-positive rate.

### 3. Procurement Pricing Strategy: Auction Simulations
* **Objective:** Analyze expected procurement costs by comparing first-price and second-price auction mechanics.
* **Data Context:** Simulated bid data for different auction environments.
* **Methods:**
  * Simulated two-bidder and four-bidder auctions.
  * Calculated empirical price distributions and variance for different auction formats.
  * Demonstrated the Revenue Equivalence Theorem through data simulation.

---

## How to Run the Code
1. Clone this repository to your local machine.
2. Ensure you have Python and Jupyter Notebook installed, along with the required libraries (`pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`).
3. Open `PROJECT WORK FILE - Final.ipynb` to view the primary analysis and modeling.

