# Sales-Analysis-Project


---

## Project Overview

Company X is a leading apparel brand in Australia, operating since 2000. Serving all demographics—kids, women, men, and seniors—the company has expanded across metropolitan and tier-1/2 cities. As Company X plans further expansion, its leadership needs deeper insights into **Q4 sales performance** to make data-driven business decisions.



---

## 🎯 Goals

* Analyze quarterly sales data across Australian states
* Identify high- and low-performing states and customer groups
* Provide actionable insights to boost performance in underperforming regions
* Deliver interactive visualizations and a comprehensive report for stakeholders

---

## 📁 Project Structure

```
├── data/
│   └── AusApparalSales4thQrt2020.csv
├── notebooks/
│   └── Sales_analysis.ipynb
├── dashboards/
│   └── sales_dashboard.png
├── README.md
```

---

##  Workflow Summary

### 1. Data Wrangling

* Checked for null/incorrect values using `isna()` and `notna()`
* Treated missing values via imputation or row removal
* Normalized numerical features (preferred over standardization)
* Used `groupby()` to aggregate and segment data

### 2. Data Analysis

* Descriptive statistics: `mean`, `median`, `mode`, `std`
* Identified:

  * Highest/lowest revenue-generating **states**
  * Highest/lowest sales by **demographic group**
* Generated weekly, monthly, and quarterly summaries

### 3. Data Visualization

* Built interactive plots and a dashboard showing:

  * State-wise sales by group
  * Group-wise sales across states
  * Time-of-day sales trends
* Included daily, weekly, and monthly trends for deep insights

>  **Preferred Library**: Seaborn (for its statistical aesthetics and ease of use)

### 4. Report Generation

* All analysis documented in a **Jupyter Notebook**
* Combined code, narrative (Markdown), and charts
* Used:

  * **Box plots** for descriptive stats
  * **Distribution plots** for group/state-wise insights

---

## 📊 Tools & Libraries

* Python 3.9+
* JupyterLab
* Pandas, NumPy, SciPy
* Seaborn, Matplotlib, Plotly

---

##  Key Insights

* Identified states with the **highest and lowest sales contributions**
* Highlighted **underperforming customer segments** and times of day
* Suggested **targeted strategies** for boosting revenue (e.g., promotional timing, regional focus)

---

##  Deliverables

* ✅ Cleaned and normalized sales dataset
* ✅ Statistical analysis and visualizations
* ✅ Interactive dashboard for business review
* ✅ Jupyter Notebook report with actionable recommendations

---

## 👨‍💼 Business Value

This analysis helps AAL:

* Make **data-backed investment decisions**
* Design **personalized marketing strategies**
* Improve **regional sales** with targeted programs


   ```

---

Let me know if you want this version in `.md` file format or customized with your name and links!
