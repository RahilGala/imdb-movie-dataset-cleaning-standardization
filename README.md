# IMDB Movie Dataset: Cleaning & Standardization (SQL)

## 📌 Project Overview
This project focuses on the End-to-End ETL (Extract, Transform, Load) process for a dataset of 250+ IMDB movie records. Using MySQL 8.0, I developed a systematic data cleaning pipeline that successfully reduced data corruption from 30% to 0%.

The primary objective was to transform inconsistent, unformatted movie metadata into a standardized, "analysis-ready" schema suitable for data visualization and machine learning.

## 🛠️ Tech Stack
Database: MySQL 8.0

Language: SQL

Tools: MySQL Workbench (or your preferred IDE)

## 🚀 Key Features & Transformations
### 1. Data Quality Improvement
Corrupted Data Elimination: Reduced error rates from 30% to 0% by identifying and fixing encoding issues and structural anomalies.

UTF-8 Encoding: Performed advanced text cleaning to correct broken character symbols and standardize movie titles and names.

### 2. Temporal Standardization
ISO Formatting: Standardized over 10 different date formats (e.g., MM/DD/YY, DD-MM-YYYY, Month DD, YYYY) into the industry-standard ISO 8601 (YYYY-MM-DD) format using STR_TO_DATE and CASE logic.

### 3. Numeric & Logic Engineering
Currency & Numeric Cleaning: Engineered transformation logic to strip special characters (symbols, commas) from revenue and budget fields, casting them into proper numeric types for calculation.

