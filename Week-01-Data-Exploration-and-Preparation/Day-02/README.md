# Day 2 – Data Cleaning & Feature Engineering

## Objective

The objective of Day 2 was to improve the quality of the dataset by cleaning missing and inconsistent data, engineering meaningful features, and validating the processed data. These steps are essential to ensure the dataset is reliable and ready for machine learning models.

---

## Tasks Performed

### 1. Data Cleaning

Performed data cleaning to improve the overall quality of the dataset.

The following tasks were completed:

- Identified and handled missing values.
- Removed duplicate records.
- Corrected inconsistent data types.
- Checked for invalid or incorrect entries.
- Prepared the dataset for further analysis.

### 2. Feature Engineering

Created new features that provide more meaningful information for analysis and predictive modeling.

The engineered features included:

- **RFM Analysis**
  - **Recency:** Number of days since the customer's last purchase.
  - **Frequency:** Total number of purchases made by each customer.
  - **Monetary:** Total amount spent by each customer.

- **Rolling Statistics**
  - Calculated rolling averages and trends to better understand changes in sales over time.

### 3. Data Validation

Validated the processed dataset using **Great Expectations** to ensure data quality.

Validation checks included:

- Missing value validation
- Data type validation
- Column consistency checks
- Range and format verification

---

## Tools & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Great Expectations

---

## Outcome

By the end of Day 2, the dataset was cleaned, enriched with new features, and validated for quality. The newly engineered features provided valuable insights into customer purchasing behavior and prepared the data for customer segmentation and forecasting in the next stages of the internship.

---

