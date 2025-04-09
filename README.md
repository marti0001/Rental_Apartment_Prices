# 🏡 Rental Apartment Prices – Predictive Model for Rent Estimation

This project focuses on building a **predictive model** to estimate **apartment rental prices** based on **textual descriptions** and **property metadata**. By collecting and processing real estate listings, the model aims to accurately predict rental prices and reveal insights into how different property features impact pricing.  

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
  <img src="https://img.shields.io/badge/BeautifulSoup-4B275F?style=for-the-badge&logo=beautifulsoup&logoColor=white" alt="BeautifulSoup"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
  <img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=plotly&logoColor=white" alt="Matplotlib"/>
</p>

---

## 🎯 Project Objectives  

### 📌 **Goal**  
The main objective is to **develop a predictive model** that estimates apartment rental prices based on:  
- **Property features** (e.g., area, number of rooms, location).  
- **Descriptive information** (e.g., listing title and description).  

✅ **Input Data:**  
- Apartment features such as **size (m²)**, **number of rooms**, and **location**.  
- **Textual data** from listing titles and descriptions.  

📤 **Output Data:**  
- Predicted **rental price** of apartments.  

---

## 🏗️ Project Workflow  

### **1. Defining the Project Goal**  
- To understand how different property features and descriptive data influence rental prices.  
- To build a model that accurately predicts rental costs.  

### **2. Data Collection**  

#### 🔍 **2.1 Web Scraping**  
- **Data Source:** Real estate listings from **OLX**.  
- **Data to Collect:**  
  - **Location:** City and district.  
  - **Apartment Details:** Area (m²), number of rooms, and rental price.  
  - **Listing Information:** Title and description text.  

#### 🏦 **2.2 Preprocessing Data**  
- ✔ **Text cleaning** 
- ✔ **Separation of features**

#### 🏦 **2.3 Data Storage**  
- **Database:**  
  - The collected text data and metadata are stored in an **SQLite** database for further analysis.  

---

## 🛠️ Technologies & Tools  

| **Category**         | **Tools & Libraries**                              |
|-----------------------|--------------------------------------------------|
| **Web Scraping**      | `BeautifulSoup`, `Requests`                      |
| **Database**          | `SQLite`                                         |
| **Programming Language** | `Python`                                      |
| **Data Analysis**     | `Pandas`, `NumPy`                                |
| **Data Visualization**| `Matplotlib`, `Seaborn`                          |
| **Machine Learning**  | (Planned for future development)                 |

---

## 🚀 Project Structure  

```bash
📦 Rental-Apartment-Prices
├── 📁 data raw
│   ├── olx_krakow_detailed_listings.csv
│   ├── olx_bydgoszcz_detailed_listings.csv
│   ├── olx_gdansk_detailed_listings.csv
│   ├── olx_lodz_detailed_listings.csv
│   ├── olx_nowy-sacz_detailed_listings.csv
│   ├── olx_poznan_detailed_listings.csv
│   ├── olx_szczecin_detailed_listings.csv
│   ├── olx_warszawa_detailed_listings.csv
│   ├── olx_wroclaw_detailed_listings.csv
├── 📁 notebooks
│   ├── Rental_Apartment_Prices_Web_Scraping.ipynb
│   ├── Rental_Apartment_Prices_Clean_data.ipynb
├── 📄 README.md
```

##  🚧 Project Status
###  🚀 **Current Phase:**  

- Cleaning and preprocessing the data.

- Exploratory Data Analysis (EDA).

- Developing and optimizing the predictive model.

### ✅ **Next Steps:** 

- Data preprocessing and feature engineering.

- Model development and hyperparameter tuning.

- Model evaluation and deployment.