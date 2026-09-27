# SpendDNA - Personal Transaction Analysis

## Project Overview

This project analyzes Rahul Sharma's transaction data from January to June 2024.

The analysis covers:
- Data cleaning and validation
- Transaction type standardisation
- Vendor extraction and mapping
- Spending category classification
- Monthly spending trends
- Time-of-day spending patterns
- Anomaly detection using z-scores
- Spending archetype detection
- Final spending overview and insights

**Dataset:** 1,310 transactions  
**Period:** January 2024 - June 2024  
**Unique vendors:** 40

---

## Key Insights

### 1. Food Delivery was the most frequent spending category

Food Delivery accounted for **364 transactions**, making it the most frequently occurring spending category in the dataset. Swiggy and Zomato were the major vendors contributing to this category.

### 2. E-commerce had the highest total spending

E-commerce was the largest spending category by amount, with total debit spending of **₹603,877**. Amazon was the largest individual vendor by debit spending, accounting for **₹328,530**.

### 3. Large transactions contributed significantly to spending anomalies

The anomaly analysis identified **30 transactions** with a z-score above 2. E-commerce accounted for **15 of these anomalies**, followed by Food Delivery with 6 and Restaurants with 5. The largest detected anomaly was an Amazon transaction of **₹22,008**.

> **Note:** The Food Delivery late-night analysis found 75 transactions between 9 PM and 1 AM, representing **20.60%** of Food Delivery transactions. This is the result obtained from the dataset.

---

## Reflection

Through this project, I learned how raw transaction data can be cleaned, transformed, categorized, and analyzed using Python and pandas.

The project helped me understand practical data science concepts such as data cleaning, data type conversion, duplicate removal, feature creation, grouping and aggregation, vendor and category classification, time-based analysis, z-score based anomaly detection, and interpreting data through summaries.

One of the main challenges was working with inconsistent transaction descriptions and formats. Mapping different descriptions belonging to the same vendor required creating and refining vendor rules.

I also learned that data analysis should be based on the actual results produced by the dataset rather than forcing results to match an expected example or checkpoint.

Overall, this project gave me practical experience with the basic workflow of a data analysis project, from raw data preparation to final reporting.

---

## AI Assistance Disclosure

AI assistance was used during this project as a learning and development aid.

AI was used to:
- Explain Python and pandas concepts
- Help structure and debug code
- Suggest approaches for data cleaning and transformation
- Assist with formatting the final report
- Help interpret and document analysis results

The dataset was processed and the analysis was executed in Google Colab. Final outputs, calculations, and results were checked against the processed dataset before inclusion in the report.

AI assistance was used as a support tool while learning and completing the project, rather than as a replacement for running and verifying the analysis.

---

## Submission

**Platform:** Google Colab  
**Repository:** GitHub / Colab link to be added after submission
