# Diwali_Sales

This project is an exploratory data analysis (EDA) on Diwali_Sales dataset consisting of 11,000 records. The dataset contains customer demographics and purchase behavior. The project was carried out using **Pandas**, **NumPy**,**Matplotlib** and **Seaborn**.

## 🔍 Objective

To perform a comprehensive data cleaning and analysis pipeline and derive business insights such as:

* Sales performance by gender, age, state, and occupation
* Patterns in purchasing behavior
* Understanding customer demographics

## 📁 Dataset

The dataset used was manually generated with typical data issues such as:

* Missing values in `Gender`, `Orders`, etc.
* Inconsistent formatting and duplicates.
* Dropped unncessary columns.
* Unstructured text.

### Columns in Cleaned Dataset:

* `Customer_ID`
* `Cust_name`
* `Age`
* `Gender`
* `State`
* `Occupation`
* `Orders`
* `Product Category`
* `Zone`
* `Product ID`
* `Marital_Status`

## 🧹 Step 1: Data Cleaning

* Converted `Age` column to integers.
* Handled missing values:

  * Replaced missing `Gender` with `Not specified`.
  * Filled missing `Orders` with the column mean.
* Converted `Amount` from string to numeric.
* Dropped the unncessary columns `Status` and `unnamed1` for consistency.

## 📊 Step 2: Data Visualization

### ✅ Plots Created:

#### 1. Gender Distribution (Bar Chart)

* Shows the count of customers by gender.

#### 2. Sales by Gender (Bar Plot)

* Compares total sales between male, female, and undefined genders

#### 3. Count of customers in each age group (Bar chart)

* Bar chart of Age group with highest number of customers.

#### 4. Sales by Age (Bar Plot)

* Compares total sales between different range of Age.

#### 5. TOP 10 States by sales(Bar Plot)

* Compares total sales between all the states and extract the TOP 10 States.

#### 6. TOP 10 States by number of orders(Bar Plot)

* Compares total number of orders between all the states and extract the TOP 10 States.

#### 7. Count of customers by Marital_Status (Bar Plot)

* Compares total counts between customers based on their marital_status.

#### 8. Sales by customers in each Gender and their Marital Status (Bar chart)

* Bar chart of Gender and Marital Status with highest number of sales.

#### 9. Count by Occupation (Bar Plot)

* Compares total counts between customers from various fields.

## 📦 Libraries Used

* **Pandas** – data manipulation and cleaning
* **NumPy** – random value generation, numerical operations
* **Matplotlib** – charts and plots
* **Seaborn** - charts and plots

## 📌 Key Insights

* Female gender group spent more than others.
* Maried Female customers contribute to the major sales.
* Customers in states like Karnataka, Maharashtra and UP dominate the revenue.
* Customers within age groups 26-35 contribute to the sales in major way.
* Customers who are working in fields of IT sector, Healthcare and Aviation tend to spend more.

## ✍️ Author

**Pramod S**
