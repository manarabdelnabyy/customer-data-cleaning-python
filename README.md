# customer-data-cleaning-python
This project demonstrates a complete data cleaning workflow using Python, Pandas, and NumPy on a customer dataset.

# 📊 Data Cleaning in Customer Dataset Using Python  

## 📌 Project Overview  
This project demonstrates how to clean and prepare a **customer dataset** using Python.  
The workflow covers everything from loading raw data to exporting a clean dataset ready for analysis.  

---

## ⚙️ Technologies Used  
- **Python**  
- **Pandas**  
- **NumPy**  

---

## 🚀 Project Steps  

1. **Import Libraries**  
   - Load Pandas and NumPy for data manipulation.  

2. **Load the Dataset**  
   - Read the CSV file into a Pandas DataFrame.  

3. **Inspect the Data**  
   - View first rows, check data types, and get summary statistics.  

4. **Handle Missing Data**  
   - Fill missing values (mean for numerical, default for categorical).  

5. **Correct Data Types**  
   - Convert dates to `datetime`.  
   - Ensure numeric columns are integers/floats.  

6. **Standardize Categorical Values**  
   - Fix inconsistent text formatting in categorical columns.  

7. **Handle Duplicates**  
   - Identify and remove duplicate rows.  

8. **Feature Engineering**  
   - Create new features (e.g., Age Groups from Age).  

9. **Rename Columns**  
   - Use clear, descriptive names for better readability.  

10. **Export Cleaned Data**  
    - Save the cleaned dataset as a new CSV file.  

---

## 📂 Project Structure  
customer-data-cleaning-python/
│── data/
│ ├── customer_sales_data.csv # Raw dataset
│ ├── cleaned_customer_data.csv # Cleaned dataset (output)
│
│── notebooks/
│ ├── data_cleaning.ipynb # Jupyter Notebook with code
│
│── README.md # Project documentation
