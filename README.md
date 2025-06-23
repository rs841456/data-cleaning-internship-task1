

# Data Cleaning and Preprocessing Task

## 📝 Objective
This project is part of a Data Analyst internship task. The goal was to clean and preprocess a raw dataset from a marketing campaign to make it analysis-ready.

---

## 📂 Files Included
- `marketing_campaign.csv` – Original dataset
- `cleaned_marketing_data.csv` – Cleaned and processed dataset
- `data_cleaning.ipynb` – Python code for preprocessing
- `screenshots/` – (Optional) Screenshots showing process

---

## 🧹 Data Cleaning Steps
1. Renamed all columns to lowercase and snake_case
2. Removed rows with missing `income`
3. Converted `dt_customer` to datetime format
4. Created new columns:
   - `age` from `year_birth`
   - `total_children` from `kidhome` + `teenhome`
   - `total_spent` from all purchase-related columns
5. Standardized categorical columns like `education` and `marital_status`
6. Handled missing values in `dt_customer` using placeholder or by dropping
7. Removed duplicates and reset the index

---

## 🛠 Tools Used
- Python
- Pandas
- Jupyter Notebook (or any IDE)



