# Dwelling-Ownership-Prediction-in-Washington-State-2023

## Project Overview
This project explores homeownership prediction in Washington State using Support Vector Machines (SVMs). The study leverages economic, demographic, and housing factors obtained from the US Census (via IPUMS USA) to classify whether a dwelling is occupied by an owner or a renter. Three SVM kernels—linear, radial, and polynomial—are used and compared to determine the most effective model.

##  Features and Methodology
- **Dataset**: Housing data from IPUMS USA, focusing on factors such as number of rooms, household income, and age.
- **Preprocessing**:
  - Data cleaning and handling missing values.
  - Encoding categorical variables (e.g., marital status, education level).
  - Feature scaling.
- **Modeling**:
  - Implemented SVM with three kernels: linear, radial (RBF), and polynomial.
  - Hyperparameter tuning using k-fold cross-validation.
  - Feature selection to determine the most influential variables.
- **Evaluation**:
  - Model accuracy comparison across different kernels.
  - Decision boundary visualization.
  - Discussion on key predictors of homeownership.
 
  ## Key Findings
- **Strongest Predictors**: Household income and number of rooms were the top factors influencing homeownership.
- **Best Performing Model**: The RBF SVM model achieved the highest accuracy of **81.3%**, slightly outperforming the polynomial (81%) and linear (80.5%) models.
- **Policy Implications**: The findings suggest that financial stability and access to larger housing play crucial roles in homeownership. Policies supporting affordable housing and financial assistance for first-time homebuyers could improve ownership rates.

## Files in the Repository
- `Housing_revised.csv` – Preprocessed dataset used for modeling.
- `Housing_Ownership_code.ipynb` – Jupyter Notebook containing the SVM implementation, visualizations, and analysis.
- `Report.pdf` – Detailed research report with computational results and discussions.

## Requirements
- Python 
- Libraries:
  - `numpy`
  - `pandas`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`

