# Data Overview

This folder contains information about the datasets used in this study. Some datasets are publicly available, while others are proprietary and **cannot be shared** due to data ownership agreements.  

## 🔒 Data Accessibility

- **Private Data**: Some datasets are proprietary and were provided by **Advanced Infrastructure Technology Ltd (AITL)**. These datasets are not included in this repository.  
- **Public Data**: Publicly available datasets used in the project are referenced below, along with links to their official sources.

## 📂 Dataset Descriptions

### **1. Main Dataset (Private - Not Included)**  
- **Secondary Electricity Supply Area (ESA)**  
  - 📌 *Source*: Advanced Infrastructure Technology Ltd. (AITL)  
  - 📌 *Description*: Contains detailed information on capacity rating and peak load for secondary electricity supply areas in five UK local authorities: Cherwell, Oxford, South Oxfordshire, Vale of White Horse, and West Oxfordshire.  
  - 📌 *Note*: This dataset is proprietary and **not included** in this repository.

### **2. Additional Datasets (Public Data with Links)**

| Dataset Name | Source | Availability |
|--------------|--------|--------------|
| **MSOA Non-Domestic Electricity Consumption (MSOA)** | Department for Energy Security and Net Zero (2024) | ✅ [Public - Link to source](https://www.gov.uk/government/statistical-data-sets/stacked-electricity-consumption-statistics-data) |
| **LSOA Domestic Electricity Consumption (LSOA)** | Department for Energy Security and Net Zero (2024) | ✅ [Public - Link to source](https://www.gov.uk/government/statistical-data-sets/stacked-electricity-consumption-statistics-data) |
| **Postcode Domestic Electricity Consumption (Postcode)** | Government dataset | ✅ [Public - Link to source](https://www.gov.uk/government/statistics/postcode-level-electricity-statistics-2022) |
| **Customer Vulnerability (CV)** | Proprietary dataset | ❌ Not shared |
| **OS AddressBase Premium (OS)** | Proprietary dataset | ❌ Not shared ([You can request from here](https://www.ordnancesurvey.co.uk/products/addressbase-premium))|
| **Primary Electricity Supply Area (PESA)** | Advanced Infrastructure Technology Ltd. (AITL) | ❌ Not shared |

---
## ⚙️ Data Preprocessing

The following features were created from the various datasets:

### **1. Non-Domestic Electricity Consumption**  
For each MSOA, we calculate the **Non-Domestic Electricity Consumption per Building**:<br>
Non-Domestic Electricity Consumption (per Building) = (Total Non-Domestic Electricity Consumption (MSOA)) / (Commercial Building (MSOA))<br>

Then, for each ESA, we calculate the **Non-Domestic Electricity Consumption**:<br>
Non-Domestic Electricity Consumption (ESA) = Non-Domestic Electricity Consumption (per Building) × Commercial Building (ESA)

### **2. Domestic Electricity Consumption**  
Similar to non-domestic electricity consumption, we calculate the **Domestic Electricity Consumption per Building** using the LSOA dataset and the number of residential buildings. The result is then aggregated for each ESA.

### **3. Postcode Domestic Electricity Consumption**  
For each ESA, we sum the domestic electricity consumption from all postcodes within that ESA.

### **4. Population**  
We aggregate the population for each ESA based on the number of residential buildings. The **average population per residential building** is first calculated using the CV and OS datasets, then multiplied by the number of residential buildings in each ESA to determine the total population.

### **5. Building Number**  
We calculate the total number of buildings in each ESA using the OS dataset. This count includes all buildings within the ESA boundary, regardless of their type.

### **6. Building Density**  
Building density is calculated by dividing the total number of buildings in each ESA by the size of the area in square kilometres (km²).

---
## ⚠️ Disclaimer

- **No datasets are provided** in this repository.
- **Proprietary datasets** from **AITL** and other sources are not included due to data ownership agreements.
- Public datasets used in this project are referenced with links to their official sources for your reference.
