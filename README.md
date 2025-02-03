# Dissertation: Filling the Missing Data in Electricity Supply Area Dataset Using Machine Learning Methods

This repository contains the code, methods, and findings from my Master's dissertation titled *"Filling the Missing Data in Electricity Supply Area Dataset Using Machine Learning Methods"*.

## Abstract
This dissertation investigates the effectiveness of various imputation methods for addressing missing values in the secondary electricity supply area dataset. Seven methods were tested: Mean/Median/Mode, k-Nearest Neighbours (KNN), Linear Regression (LR), Random Forest (RF), Multilayer Perceptrons (MLP), Inverse Distance Weighting (IDW), and Geographically Weighted Regression (GWR). This study found that MLP and RF outperformed simpler methods, significantly reducing error rates and capturing non-linear relationships in the data. However, none of the methods achieved perfect accuracy, particularly with high missing data percentages. The findings suggest that while advanced methods help improve results, there is still a need for better feature selection and more realistic simulation of missing data. Future studies should focus on selecting features that better capture important relationships and on simulating missing data patterns that mirror real-world situations. Overall, this research highlights the significance of selecting appropriate imputation methods for complex datasets and offers ways to improve prediction accuracy in the electricity supply area.

**Keywords**: Imputation Methods, Missing Data, Multilayer Perceptrons, Electricity Supply Area.



## Key Components:
1. **Dissertation Document**:  
   A PDF copy of the full dissertation document, including all analyses, results, and discussions.
   - `dissertation.pdf`

2. **Code**:  
   Python scripts and Jupyter notebooks used for data cleaning, imputation, and machine learning model implementation.
   - `code/`: Folder containing Python scripts.
   - `notebooks/`: Folder with Jupyter notebooks for analysis.

3. **Results & Findings**:  
   Visualizations, tables, and key findings derived from the analysis in the dissertation.
   - `results/`: Folder containing visualizations, charts, and tables.

4. **Datasets**:  
   Datasets used in the analysis (note: proprietary datasets are not included).
   - `data/`: Folder containing publicly available datasets used for analysis.

---

## License
This repository is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** License.  
You are free to share and adapt this work for **non-commercial purposes**, with appropriate attribution.

For more details, visit: [CC BY-NC 4.0 License](https://creativecommons.org/licenses/by-nc/4.0/)

**Note**: Proprietary datasets from **Advanced Infrastructure Technology Ltd.** are **not included** in this repository due to confidentiality agreements. Some parts of the work may not be publicly accessible due to these restrictions.

---

## Citation
If you use or reference this work, please cite it as follows:

Huang, L.-Y. (2024). *Filling the Missing Data in Electricity Supply Area Dataset Using Machine Learning Methods*. Master’s Dissertation, City Univeristy of London, London, UK.

---

## Acknowledgments
I would like to thank **Advanced Infrastructure Technology Ltd.** for their collaboration and for providing the datasets used in this research. I also appreciate the guidance of my dissertation supervisor, **Dr. Aidan Slingsby**.
