# 🛒 Customer Shopping Behavior Analysis: Driving E-Commerce Strategy

## 🎯 Project Overview

This is an end-to-end data analysis project focused on understanding and optimizing customer shopping behavior within an e-commerce context. Utilizing a dataset of **3,900 customer transactions** , this project delivers actionable, data-driven strategies to improve customer loyalty, boost subscriptions, and enhance marketing efficiency.

The process spanned data preparation in Python, structured analysis using SQL, and final presentation in a Power BI dashboard.

## 🛠️ Technologies & Tools

| Category | Tool | Key Application |
| :--- | :--- | :--- |
| **Data Preparation** | Python (Pandas) | Data cleaning, imputation, and feature engineering (e.g., age groups) [cite: 32, 36, 39, 158] |
| **Data Storage & Analysis**| PostgreSQL |Loaded cleaned data for advanced analytical SQL queries [cite: 41, 169, 171] |
| **Visualization** | Power BI | Created the interactive **Customer Behavior Dashboard** for business stakeholders [cite: 207] |

## ⚙️ Data Preparation & Cleaning Pipeline

]The project involved a rigorous data preparation phase (Data Loading & Exploration, Data Cleaning, and Feature Engineering [cite: 30]):

1.  **Exploration & Standardization:** Initial inspection of the 3,900-row, 18-column dataset[cite: 5, 150, 151]. Standardized column names to snake\_case[cite: 36, 164].
2. **Missing Data Handling:** Handled **37 missing `Review Rating` values** using **median imputation** based on the product category[cite: 36, 156, 163].
3. **Feature Engineering:** Created the `age_group` column by binning customer ages[cite: 39, 166]. [cite_start]Calculated `purchase_frequency_days`[cite: 39, 167].
4.  **Redundancy Check:** Dropped the redundant `promo_code_used` column[cite: 39, 168].

## 📊 Key Findings & Strategic Insights (SQL Analysis)

### 1. Revenue Drivers by Gender and Age

* ]**Gender Skew:** **Male customers drive 68% of the revenue**, generating **\$157,890** compared to \$75,191 from female customers[cite: 46, 47, 181, 178].
***Age Group Leader:** **Young Adults** lead revenue generation at **\$62,143**, followed by middle-aged customers[cite: 106, 205].

### 2. Customer Segmentation and Loyalty

* The customer base is heavily skewed towards **Loyal Customers** (**80%**, 3,116 customers)[cite: 74, 198].
* The **Returning Customers** segment (**18%**, 701 customers) represents the primary opportunity for loyalty program conversion[cite: 75, 82, 198].
* Only **2%** (83 customers) are categorized as **New Customers**[cite: 80, 198].

### 3. Subscription Performance (The Value Gap)

***Subscribers** (27%, 1,053 customers) have an average spend of **\$59.49**[cite: 86, 88, 92, 193].
* **Non-Subscribers** (73%, 2,847 customers) have a similar average spend of **\$59.87**[cite: 93, 89, 95, 193].
* **Insight:** The similar spending patterns suggest the current subscription benefits require a **stronger value proposition** to incentivize the large non-subscriber base to convert[cite: 90].

### 4. Top-Rated Products

The highest average review ratings belong to:
***Gloves:** 3.86 [cite: 53, 187]
* **Sandals:** 3.84 [cite: 58, 187]
* **Boots:** 3.82 [cite: 64, 187]

## 🚀 Business Recommendations

The analysis led to five key strategic recommendations for immediate implementation[cite: 135]:

1. **Boost Subscriptions:** Promote exclusive perks and enhanced value to convert the **73% non-subscriber base** into recurring revenue[cite: 136, 243].
2.  **Customer Loyalty Programs:** Implement targeted rewards programs to move the **701 Returning Customers** into the highly valuable Loyal segment[cite: 137, 138, 246].
3.  **Targeted Marketing:** Focus campaigns on high-revenue segments: **Young Adults** and existing **Express-Shipping Users** for maximum ROI[cite: 143, 249].
4. **Product Positioning:** Highlight top-rated products (**Gloves, Sandals, Boots**) and current best-sellers in marketing campaigns to leverage customer satisfaction[cite: 140, 141, 248].
5. ]**Review Discount Policy:** Strategically review the use of discounts, especially after identifying **839 high-spending discount users**, to balance promotional sales with margin control[cite: 139, 182, 247].

---






---
