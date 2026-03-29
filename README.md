# 🌍 World Database SQL Analysis

## 📌 Project Overview

This project demonstrates SQL query execution and data analysis using the **World database**. The dataset contains information about countries, cities, and languages, and is used to perform various SQL operations through a Jupyter Notebook.

---

## 🗂️ Dataset Description

The database consists of three main tables:

### 🏙️ City

* Contains information about cities around the world
* Attributes: `ID`, `Name`, `CountryCode`, `District`, `Population`

### 🌎 Country

* Stores country-level data
* Attributes: `Code`, `Name`, `Continent`, `Region`, `Population`, `GNP`

### 🗣️ CountryLanguage

* Contains languages spoken in each country
* Attributes: `CountryCode`, `Language`, `IsOfficial`, `Percentage`

--

## 🛠️ Technologies Used

* MySQL
* Python (mysql-connector)
* Jupyter Notebook

---

## ▶️ How to Run the Project

1. Import the `world.sql` file into MySQL
2. Start MySQL server (XAMPP or MySQL Workbench)
3. Open the Jupyter Notebook (`.ipynb` file)
4. Run all cells to execute SQL queries

---

## 🎯 Learning Outcomes

* Hands-on experience with relational databases
* Writing and executing SQL queries
* Understanding table relationships and joins
* Connecting MySQL with Python using Jupyter Notebook

---

## 🚀 Future Improvements

* Add data visualizations using Python (Matplotlib/Seaborn)
* Perform advanced SQL queries (subqueries, views)
* Build a simple dashboard for insights

---

---
