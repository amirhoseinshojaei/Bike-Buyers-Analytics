# Bike-Buyers-Analytics

This project involves cleaning and analyzing a dataset related to bike buyers to improve data quality, perform in-depth analysis, and create a professional, dynamic dashboard for data visualization.

## Project Tasks:

### 1. **Data Statistics:**
   - **Total Records:** 1026
   - **Blank Records:** 0

### 2. **Data Cleaning:**
   - Removed duplicate entries: **26 duplicates found and removed**.
   - Ensured ID column values are **5 digits long** using an `IF` formula to check and clean.
   - Improved **Martial Status** column by changing values:
     - "s" → "Single"
     - "m" → "Married"
   - Enhanced **Gender** column for better readability:
     - "f" → "Female"
     - "m" → "Male"
   - Changed **Income** column data type to **Number** for better readability in the database.
   - Trimmed **White Spaces** in the **Education** column for improved quality using the `TRIM` function.

### 3. **Data Categorization:**
   - Added **Commute Category** column to classify **Commute Distance** into three groups:
     - "Short Commute"
     - "Medium Commute"
     - "Long Commute"
   - Added **Age-Group** column for better analysis by categorizing ages into four groups:
     - "Young Adults"
     - "Adults"
     - "Middle-Aged"
     - "Seniors"

### 4. **Pivot Tables and Charts:**
   - Created a new sheet named **"Pivot Tables"** for various analytical insights.
   - **Sum of Income** by **Martial Status** & **Gender** with trend line showing income differences between "Single" and "Married".
   - **Sum of Income** by **Age-Group**, **Region**, and **Purchase Bike**.
   - **Count of Purchased Bikes** by **Gender** & **Age-Group**.
   - **Sum of Income** by **Education** & **Occupation**.
   - **Count of Purchased Bikes** by **Home Owner** & **Region**.
   - **Commute Distance per Region**.
   - **Sum of Cars** by **Region** & **Children**.

### 5. **Dashboard Creation:**
   - Built a **dynamic dashboard** for data visualization with interactive elements.

## Screenshots:
   Below is the screenshot of the **Dynamic Dashboard** created in the project:

   ![Dashboard Screenshot](https://github.com/amirhoseinshojaei/Bike-Buyers-Analytics/blob/main/Screenshot%202025-02-06%20020256.png)
   ![Dashboard Screenshot](https://github.com/amirhoseinshojaei/Bike-Buyers-Analytics/blob/main/Screenshot%202025-02-06%20020417.png)
   ![Dashboard Screenshot](https://github.com/amirhoseinshojaei/Bike-Buyers-Analytics/blob/main/Screenshot%202025-02-06%20020430.png)

## Technologies Used:
   - **Excel** (Pivot Tables, Data Cleaning, Formulas)
   - **Data Analysis** & **Data Visualization**

## Conclusion:
   This project provides detailed insights and allows for easy reporting and decision-making through the use of dynamic charts, dashboards, and categorized data.

