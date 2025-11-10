# MSc AI & Data Science – Project 1  
Introduction to Programming – Customer Data Preprocessing (University of Hull)

Student: Omowumi Abimbola Emmanuel   
University: University of Hull  
Programme: MSc Artificial Intelligence and Data Science  
Module: Introduction to Programming  

## Project overview

This repository contains my first MSc assignment, focused on working with a customer dataset and preparing it for analysis.

Main tasks:
- Reading CSV data and converting it into nested JSON structures
- Cleaning and validating customer fields (dependants, credit cards, etc.)
- Creating multiple JSON views of the data (retired, employed, commute, flagged cards)
- Visualising key relationships using Pandas and Seaborn

## Files

Notebook:
- Introduction to Programming-Project Assignment Notebook.ipynb

JSON outputs:
- processed.json – all processed and nested customer records
- retired.json – customers marked as retired
- employed.json – customers with a valid employer
- remove_ccard.json – customers with credit cards valid for more than 10 years
- commute.json – customers with a Salary-per-Km metric, sorted

Plots:
- age_hist_binwidth5.png – age distribution with 5-year bins
- dependants_hist.png – number of dependants distribution
- age_by_marital_status.png – age distribution by marital status
- distance_salary_scatter.png – commuted distance vs salary
- age_salary_scatter.png – age vs salary
- age_salary_dependants_scatter.png – age vs salary coloured by dependants

## Tools

- Python
- Jupyter Notebook
- Pandas
- Seaborn
- Matplotlib

---

This repo marks the start of my data science journey. Future projects will include more advanced ML, analytics and AI work as I progress through the MSc programme.
