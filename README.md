# Dissertation: Filling the Missing Data in Electricity Supply Area Dataset Using Machine Learning Methods

This repository contains the code, methods, and findings from my Master of Data Science dissertation at City, University of London, titled: *"Filling the Missing Data in Electricity Supply Area Dataset Using Machine Learning Methods"*.

## 📖 Abstract
This dissertation investigates the effectiveness of various imputation methods for addressing missing values in the secondary electricity supply area dataset. Seven methods were tested: Mean/Median/Mode, k-Nearest Neighbours (KNN), Linear Regression (LR), Random Forest (RF), Multilayer Perceptrons (MLP), Inverse Distance Weighting (IDW), and Geographically Weighted Regression (GWR). This study found that MLP and RF outperformed simpler methods, significantly reducing error rates and capturing non-linear relationships in the data. However, none of the methods achieved perfect accuracy, particularly with high missing data percentages. The findings suggest that while advanced methods help improve results, there is still a need for better feature selection and more realistic simulation of missing data. Future studies should focus on selecting features that better capture important relationships and on simulating missing data patterns that mirror real-world situations. Overall, this research highlights the significance of selecting appropriate imputation methods for complex datasets and offers ways to improve prediction accuracy in the electricity supply area.

**Keywords**: Imputation Methods, Missing Data, Multilayer Perceptrons, Electricity Supply Area.


## 📂 Repository Structure  

1. **Dissertation & Reports**  
   - 📄 `dissertation.pdf` – Full dissertation, including analyses, results, and discussions.  
   - 📄 `proposal.pdf` – Initial research proposal outlining objectives and methodology.  

2. **Code**  
   - 📂 `code/` – Jupyter notebooks for different stages of the analysis:  
     - 📘 `1_Features_EDA.ipynb` – Feature engineering and exploratory data analysis.  
     - 📘 `2_Capacity_Rating_Imputation.ipynb` – Imputing missing values for Capacity Rating.  
     - 📘 `3_Peak_Load_Imputation.ipynb` – Imputing missing values for Peak Load.  
     - 📘 `4_Impute_Actual_Missing.ipynb` – Final imputation of missing values in the dataset.  

3. **Datasets**  
   - 📂 `data/` – This folder **does not contain datasets** but includes a README describing the datasets used in the analysis.  

---

## 📜 License

[![License: CC BY-ND 4.0](https://img.shields.io/badge/License-CC%20BY--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nd/4.0/)

- The **code** in this repository is licensed under the **Creative Commons Attribution-NoDerivatives 4.0 International License**.  
  🔹 **You may** view and download the code.  
  🔹 **You may NOT** modify, adapt, or reuse it in any form.  
  🔹 **Proper attribution is required** when referencing this work.

- **Datasets**: No datasets are included in this repository. Any datasets used are either proprietary (owned by **Advanced Infrastructure Technology Ltd.**) or publicly available.

- **Collaboration**: This project was carried out in collaboration with **Advanced Infrastructure Technology Ltd.** under agreed research terms. All proprietary information from the company has been excluded.

---

## Citation
If you use or reference this work, please cite it as follows:

Huang, Ling-Yun. (2024). *Filling the Missing Data in Electricity Supply Area Dataset Using Machine Learning Methods*. Master’s Dissertation, City Univeristy of London, London, UK.

---

## Acknowledgments
I would like to thank **Advanced Infrastructure Technology Ltd.** for their collaboration and for providing the datasets used in this research. I also appreciate the guidance of my dissertation supervisor, **Dr. Aidan Slingsby**.
