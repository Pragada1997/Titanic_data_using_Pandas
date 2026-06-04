# Titanic Data Cleaning and Analysis using Pandas

## Project Overview

This project focuses on cleaning and analyzing the Titanic dataset using Python and Pandas. The goal is to prepare the dataset for analysis by handling missing values, removing unnecessary data, and extracting meaningful insights related to passenger survival.

## Objectives

- Remove null values from the dataset.
- Remove unwanted rows and columns.
- Calculate the overall survival rate.
- Analyze survival rate based on:
  - Gender
  - Age
  - Passenger Class
- Calculate the total number of male and female passengers.
- Cross-validate gender-based survival data.
- Identify correlation between passenger class and survival.

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook / VS Code

## Dataset

Dataset Used: `titanic.dataset.csv`

The dataset contains passenger information such as:

- Passenger ID
- Name
- Age
- Gender
- Passenger Class
- Fare
- Embarked
- Survival Status

## Project Workflow

### 1. Data Loading

- Imported the Titanic dataset using Pandas.
- Examined dataset structure and data types.

### 2. Data Cleaning

- Identified missing values.
- Removed or handled null values.
- Dropped unnecessary columns.
- Removed unwanted rows where required.
- Verified cleaned dataset.

### 3. Exploratory Data Analysis (EDA)

#### Overall Survival Rate
- Calculated the percentage of passengers who survived.

#### Survival Rate by Gender
- Compared male and female survival rates.

#### Survival Rate by Age
- Analyzed survival distribution across age groups.

#### Survival Rate by Passenger Class
- Examined survival trends among different passenger classes.

### 4. Gender Analysis

- Counted total male passengers.
- Counted total female passengers.
- Cross-validated survival counts by gender.

### 5. Correlation Analysis

- Investigated the relationship between Passenger Class and Survival.
- Identified whether higher passenger classes had better survival chances.

## Key Insights

- Female passengers had a significantly higher survival rate than male passengers.
- First-class passengers showed better survival probabilities.
- Passenger age influenced survival outcomes.
- Passenger class demonstrated a noticeable correlation with survival.
