# Business-Funding-Nigeria-Data-Cleaning
🔹 Project Overview

This project focuses on cleaning and preprocessing a Business Funding dataset from Nigeria.
The dataset contains information about funded businesses, including:

Website domains

Funding amounts (raw and normalized)

Financing types

Categories (industries)

Investors and investor count

The goal was to transform the raw, messy data into a well-structured dataset ready for analysis.

🔹 Steps Taken

Loaded dataset and inspected its structure.

Standardized column names for easier handling (lowercase, underscores).

Removed duplicates to ensure data integrity.

Handled missing values strategically:

Dropped columns with more than 60% missing values.

Dropped rows with missing entries in critical fields (investors, investors_count).

Verified dataset cleanliness with .isnull().sum() and .shape.

🔹 Key Observations

A large portion of financing type and effective date data was missing.

Some categories and funding amounts were well structured and ready for analysis.

The cleaned dataset can now be used to explore:

Which industries attract the most funding

Distribution of financing types

Relationship between investors count and funding amount

🔹 Reflections

Preprocessing is critical: raw data almost always comes messy.

Every decision (dropping, filling, renaming) impacts the reliability of insights.

A clean dataset builds trust in future analysis and models.
