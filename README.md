## 🏦 Bank Loan Default Risk Analysis (Excel EDA Project)

**Type:** Case Study / Exploratory Data Analysis  
**Tool Used:** Microsoft Excel, Microsoft PowerPoint  
**Dataset:** `previous_application.xlsx` (50,000+ loan applications, 96 variables)  
**Focus:** Loan approval risk, customer segmentation, outlier detection, and imbalance analysis

---

## 📌 Objective

To investigate customer behavior and loan performance to help a finance company reduce risk and improve loan approval decisions. The project focuses on applicants with payment difficulties vs. those with timely payments to identify patterns of default risk.

---

## 🛠 Tools & Techniques

- Excel formulas: `COUNTBLANK`, `QUARTILE.INC`, `IF`, `MODE`, `AVERAGE`, `MEDIAN`
- Data cleaning: Handled missing values by removal or imputation
- Outlier detection: Interquartile Range (IQR) method
- Univariate, segmented univariate, and bivariate analysis
- Data imbalance calculation using ratio metrics
- Correlation matrix (heatmap-style visualization)

---

## 📊 Key Insights

### 🧹 Missing Values
- Columns with >50% missing were removed
- Columns with <50% nulls were imputed using average, median, or mode

### 🧮 Outlier Detection
- Validated extreme income and loan values
- Flagged and removed invalid entries (e.g., negative children count)

### ⚖️ Data Imbalance
- Only **8.75%** of applicants faced payment difficulty (Target = 1)
- 91.25% made payments on time → highly imbalanced dataset

### 🔍 Univariate & Bivariate Analysis
- Max income bin: ₹100k–125k
- Most loans approved in ₹1L–₹5L range
- `Cash Loans` dominated over `Revolving Loans`
- High correlations found with: `goods_price`, `days_birth`, `days_employed`, and `annuity`

---

## 📁 Deliverables

- `previous_application reduced.xlsb` — Cleaned EDA dataset  
- `Bank loan Study case.pptx` — Insight summary slides  
- `README.md` — This documentation  

---

## 💼 Resume/Portfolio Description

> Performed end-to-end exploratory data analysis on 50,000+ loan applications using Excel. Cleaned missing data, detected outliers using IQR, calculated data imbalance ratios, and conducted univariate/bivariate analysis to identify top drivers of loan defaults. Presented findings in a strategic PowerPoint report for executive stakeholders.

---

## 🔗 Related Skills

- Financial Analytics
- Excel-based Data Exploration
- Risk Modeling Foundations
- Visual Presentation of Data

