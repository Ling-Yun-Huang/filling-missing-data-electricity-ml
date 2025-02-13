# 📂 Code Overview

This folder contains Python scripts and Jupyter notebooks used for data processing, exploratory analysis, and machine learning model implementation in the dissertation project.

### 📂 Code Structure

| File/Folder                       | Description                                                                 |
|------------------------------------|-----------------------------------------------------------------------------|
| `1_Features_EDA.ipynb`             | Exploratory Data Analysis (EDA) and feature engineering, including data visualization and summary statistics. |
| `2_Capacity_Rating_Imputation.ipynb` | Machine learning models for imputing missing values in Capacity Rating.     |
| `3_Peak_Load_Imputation.ipynb`     | Machine learning models for imputing missing values in Peak Load.           |
| `4_Impute_Actual_Missing.ipynb`    | Final imputation applied to actual missing values in the dataset. Proposes other methods for potentially imputing missing values.          |

### ⚙️ Code Details

1. **Features & Exploratory Data Analysis (EDA)**
   - Loads and inspects datasets.
   - Generates visualizations (e.g., distributions, correlations).
   - Performs feature engineering.

2. **Capacity Rating Imputation**
   - Applies machine learning models to estimate missing Capacity Rating values.
   - Models tested: Random Forest, Multilayer Perceptron (MLP), etc.
   - Compares model performance with a validation dataset.

3. **Peak Load Imputation**
   - Similar approach to Capacity Rating, but for Peak Load.
   - Feature selection based on correlation analysis.

4. **Impute to Actual Missing Values**
   - Uses trained models to fill in missing values in the dataset.
   - Validates imputed results against known patterns.
   - Proposes additional methods for simulating missing values.

### 📝 License

This project is licensed under the [Creative Commons Attribution-NoDerivatives 4.0 International License](../LICENSE).

- **You may** view and download the code.
- **You may NOT** modify, adapt, or reuse it in any form.
- **Proper attribution is required** when referencing this work.
