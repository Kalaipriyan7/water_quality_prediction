# Water Quality Prediction - Kalaipriyan

This project focuses on predicting multiple water quality parameters using machine learning. It employs a `MultiOutputRegressor` wrapped around a `RandomForestRegressor` to perform multi-target regression efficiently.

Developed as part of a one-month **AICTE Virtual Internship** sponsored by **Shell** in **June 2025**.

---

## Overview

Access to clean water is a critical global challenge. This project aims to build a machine learning model capable of accurately predicting several water quality metrics, enabling early detection of water pollution and supporting proactive intervention.

---

## Objectives

- Collect and preprocess real-world water quality datasets.
- Apply supervised machine learning techniques for multi-output regression.
- Build a pipeline using `MultiOutputRegressor` with `RandomForestRegressor`.
- Evaluate the model using standard regression performance metrics.

---

## Technologies Used

- **Python 3.12**
- **Pandas**, **NumPy** – Data manipulation and preprocessing
- **Scikit-learn** – Machine learning modeling and evaluation
- **Matplotlib**, **Seaborn** – Data visualization
- **Jupyter Notebook** – Development and experimentation

---

## Predicted Parameters

The model is trained to predict the following water quality parameters:

- NH₄ (Ammonium)
- BOD5 (Biochemical Oxygen Demand)
- Colloids
- O₂ (Dissolved Oxygen)
- NO₃ (Nitrate)
- NO₂ (Nitrite)
- SO₄ (Sulfate)
- PO₄ (Phosphate)
- Cl (Chloride)

---

## Machine Learning Approach

- **Model**: MultiOutputRegressor with RandomForestRegressor
- **Type**: Multi-target regression
- **Steps**:
  - Data loading and cleaning
  - Feature scaling and selection
  - Model training and testing
  - Performance evaluation

---

## Evaluation Metrics

The model performance was assessed using:

- Coefficient of Determination (**R² Score**)
- **Mean Squared Error (MSE)**

Performance was acceptable across all predicted parameters, demonstrating the model's capability to generalize well on unseen data.

---

## Project Structure

```bash
water-quality-prediction/
│
├── data/                     # Raw and cleaned datasets
├── notebooks/                # Jupyter notebooks for exploration and modeling
├── models/                   # Trained model files (if any)
├── src/                      # Core source code (functions, utils)
├── README.md                 # Project documentation
├── requirements.txt          # Python dependencies
└── LICENSE                   # License file
