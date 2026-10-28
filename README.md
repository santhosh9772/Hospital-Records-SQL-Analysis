Hospital Records SQL Analysis

📌 Project Overview

This project focuses on analyzing hospital records using MySQL. It uses SQL queries to retrieve, filter, update, and analyze information about patients, doctors, provinces, and hospital admissions.

🎯 Objectives

Retrieve patient and doctor information.

Filter patient records based on specific conditions.

Handle missing allergy values.

Analyze hospital admissions and patient statistics.

Use SQL joins to combine data from multiple tables.

Generate summaries using aggregate functions.

🛠️ Tools & Technologies

Database: MySQL

Language: SQL

Concepts: Data Filtering, Joins, Subqueries, Aggregation, Grouping, Sorting, Data Cleaning

🗂️ Database Tables

The project creates the hospital_db database with four tables:

doctors – Doctor IDs, names, and specialties.

patients – Patient details, gender, date of birth, allergies, height, weight, and province.

province_names – Province IDs and province names.

admissions – Patient admissions, admission dates, discharge dates, diagnoses, and doctor IDs.

📊 Key SQL Operations

SELECT and WHERE: Retrieve specific patient records.

LIKE: Find names that start or end with specific letters.

BETWEEN and IN: Filter records by ranges or specific IDs.

UPDATE: Replace missing allergy values with NKA.

CONCAT: Combine first and last names.

JOIN: Combine patient, doctor, and province information.

COUNT, SUM, MAX, MIN: Calculate totals and find extreme values.

GROUP BY and HAVING: Summarize patient and admission data.

ORDER BY: Sort records by name, date, or count.

Subqueries: Identify patients with the greatest height.

UNION ALL: Combine patient and doctor names.

CASE: Calculate an obesity indicator using BMI.
