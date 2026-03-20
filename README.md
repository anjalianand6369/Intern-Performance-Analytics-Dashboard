# Intern-Performance-Analytics-Dashboard 

🔹 Sprint 1: Data Collection And Preparation

🎯 Objective

 The objective of Sprint 1 is to clean and prepare the raw intern performance dataset to make it suitable for analysis and visualization. This involves handling missing values, transforming data, and ensuring consistency across all features.

📁 Dataset Overview

The dataset contains 1000 intern records with attributes related to:

Demographics (age, gender)

Performance (task completion, project score)

Behavioral metrics (attendance, punctuality)

Skill scores (technical, communication, teamwork)

Engagement (training hours, certifications)

🧹 Data Cleaning Steps

✔ Handling Missing Values

Identified missing values in:

communication_score

technical_score

mentor_feedback_score

Filled missing values using median imputation to maintain data integrity.

✔ Standardizing Categorical Data

Converted text values to lowercase and removed extra spaces.

Cleaned columns:

gender

department

extra_activities

✔ Encoding Categorical Variables

Converted extra_activities:

yes → 1

no → 0

🔄 Data Transformation
✔ Internship Duration Cleaning

Handled mixed values like "Six", "6 months"

Steps performed:

Converted text to lowercase

Mapped word-based numbers to digits

Extracted numeric values

Converted to integer format

🔁 Duplicate Handling

Checked for duplicate records

Removed duplicates to ensure data quality

⚙️ Feature Engineering

Created new features for better analysis:

Overall Performance Score

Average of task completion, project score, and technical score

Soft Skills Score

Average of communication, teamwork, and initiative scores

Discipline Score

Attendance adjusted with late submissions

✅ Data Validation

Ensured no missing values

Verified correct data types

Confirmed cleaned columns contain valid values

Reviewed summary statistics for consistency

💾 Final Output

Cleaned dataset saved as:
cleaned_intern_dataset.csv
