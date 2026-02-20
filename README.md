# Credit & Portfolio Risk Modelling Project

Project Overview

This project develops an end-to-end credit and portfolio risk analytics framework designed to assess borrower default risk and quantify portfolio exposure under normal and stressed market conditions.

The objective was to simulate a real-world risk analytics workflow used in banks, investment firms, and fintech companies — combining credit modelling, market risk measurement, and stress testing into a structured and reproducible pipeline.

Business Objective

Financial institutions must quantify:

Probability of borrower default

Expected portfolio loss

Market risk exposure

Portfolio resilience under stress scenarios

This project addresses those objectives through predictive modelling and risk metric implementation.

📂 Project Structure
investment-risk-analytics/
│
├── data/ (raw and processed datasets)
├── pipelines/ (data cleaning & feature engineering scripts)
├── models/ (PD model, VaR, volatility, stress testing)
├── notebooks/ (EDA & modelling workflow)
├── dashboards/ (risk visualisation layer)
├── README.md

# Methodology

1️⃣ Data Preparation

Cleaned and validated financial datasets

Handled missing values and outliers

Engineered credit risk features (DTI ratio, utilisation rate, loan grade encoding)

2️⃣ Credit Risk Modelling

Built a Logistic Regression model to estimate Probability of Default (PD)

Evaluated performance using ROC curve, AUC, confusion matrix

Identified key predictors of default risk

3️⃣ Portfolio Risk Metrics

Calculated Expected Loss using:

Expected Loss = PD × LGD × EAD

Implemented:

Historical Value at Risk (VaR)

Parametric VaR

Monte Carlo simulation

4️⃣ Volatility Modelling

Applied GARCH modelling to forecast conditional volatility

Analysed volatility clustering effects on tail risk

5️⃣ Stress Testing

Simulated adverse scenarios:

Market shock (-30%)

Credit spread widening

Increase in default rate

Measured impact on:

Portfolio value

Loss distribution

Risk capital requirement

📈 Key Outcomes

Successfully classified high-risk borrowers using PD modelling

Quantified downside risk exposure at 95% and 99% confidence levels

Demonstrated how stress scenarios materially increase expected losses

Built a reproducible risk analytics pipeline aligned with industry practices

🛠 Tech Stack

Python

Pandas & NumPy

Scikit-learn

Matplotlib / Seaborn

ARCH (GARCH modelling)

SQL (data validation & extraction)

Power BI (risk dashboard)
