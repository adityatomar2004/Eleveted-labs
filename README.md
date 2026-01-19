# Task 1: Excel Basics - Data Cleaning & Formatting

## 📊 Project Overview
This project focuses on cleaning and standardizing a raw dataset using Microsoft Excel. The goal was to transform a messy real-world dataset into a structured format ready for analysis, ensuring data integrity and consistency.

**Task Source:** Elevate Labs Data Analyst Internship  
**Dataset Used:** Netflix Movies and TV Shows

---

## 🛠️ Tools Used
* **Microsoft Excel** (Data Cleaning, Formatting, Logic Formulas)
* **CSV/XLSX** (File Handling)

---

## 🧹 Data Cleaning Process
Following the internship task guidelines, I performed the following steps to clean the data:

### 1. Setup & Exploration
* Imported the raw CSV data into Excel.
* [cite_start]**Freeze Panes:** Locked the top header row to maintain visibility while scrolling.
* [cite_start]**Filters:** Applied filters to all columns to inspect unique values and identify inconsistencies.

### 2. Handling Missing Values
* [cite_start]Identified blank cells using filtering and Conditional Formatting[cite: 3].
* **Imputation Strategy:**
    * **Directors/Cast/Country:** Filled missing values with "Unknown" to preserve row data rather than deleting it.
    * **Date Added:** Validated format and flagged irregularities.

### 3. Removing Duplicates
* [cite_start]Checked for duplicate records based on the unique `show_id` column[cite: 4].
* Created a backup of the data before removal to prevent data loss.

### 4. Text Standardization
* Cleaned text columns (Title, Rating, Category) to remove extra spaces and inconsistent casing.
* [cite_start]**Functions Applied:** Used logic similar to `TRIM()` and `PROPER()` to ensure clean text entry[cite: 5].

### 5. Data Quality Documentation
* [cite_start]Created a new column named **`Data_Quality_Notes`**[cite: 6].
* Added specific notes (e.g., "Missing Director imputed", "Missing Country imputed") to document changes made during the cleaning process.

---

## 📂 Files in Repository
[cite_start]This repository contains the three required deliverables[cite: 8]:

1.  **`Raw_Data.xlsx`** - The original, unprocessed dataset.
2.  **`Cleaned_dataset.xlsx`** - The final Excel workbook containing the "Cleaned_Data" sheet with formatting and quality notes.
3.  **`cleaned_dataset.csv`** - The exported CSV version of the cleaned data for future analysis pipelines.

---

## 💡 Key Learnings
* Importance of keeping **Raw** and **Cleaned** data in separate tabs/files[cite: 5].
* [cite_start]Difference between deleting data vs. imputing values to maintain dataset size[cite: 9].
* [cite_start]How to validate data types (Dates vs. Text) to prevent analysis errors[cite: 4].
