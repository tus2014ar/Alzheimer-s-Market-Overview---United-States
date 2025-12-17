# Alzheimer’s Market Overview — United States  
### TRx-Based Market Analysis & Interactive Dashboard

This project analyzes the **United States Alzheimer’s prescription (TRx) market** using an interactive dashboard built in **Python**. The dashboard helps understand how **brands, physician specialties, and sales channels** contribute to market trends over time.

As part of this project, the **same business problem was also implemented in Tableau**, allowing a direct comparison between **Python-based dashboards and Tableau dashboards**.

---

## Business Objective
The primary objective of this project is to:
- Analyze **Total Prescriptions (TRx)** trends over time
- Identify **brand-level momentum**
- Understand **physician specialty contributions**
- Examine **sales channel mix and shifts**
- Enable data-driven decision-making for commercial and marketing teams

---

## Dashboard Overview (Python)
The Python dashboard provides:
- **Time-series analysis** of TRx by brand
- **Specialty-level TRx contribution and share**
- **Specialty × Channel heatmap** for opportunity identification
- **Channel mix trends over time**
- Fully **interactive visuals** with hover, filters, and toggles

The dashboard is exported as a **standalone HTML file**, making it easy to share without requiring a server.

---

## Dataset Summary
- **Rows:** 202,499  
- **Columns:** 10  
- **Key Measures:**  
  - Total TRx  
  - TRx Pharmacy Dollar Volume  
- **Dimensions:**  
  - Brand  
  - Physician Specialty  
  - Sales Channel  
  - Time (Monthly)

Missing demographic values are retained as `"UNSPECIFIED"` to preserve data completeness and avoid bias.

---

## Technology Stack
### Python Dashboard
- Python
- Pandas & NumPy (data processing)
- Plotly (interactive visualizations)
- HTML export for dashboard sharing

### Tableau Dashboard
- Tableau Desktop
- Drag-and-drop visual analytics
- Built-in filters and parameters

---

## Python vs Tableau — Key Differences Observed

### 1. Data Preparation
**Python (Better)**
- Full control over data cleaning, feature engineering, and transformations
- Complex aggregations and custom metrics are easier and more transparent
- Reproducible and script-based

**Tableau**
- Faster for simple aggregations
- Limited flexibility for advanced preprocessing
- Heavily dependent on data being clean beforehand

---

### 2. Flexibility & Customization
**Python (Better)**
- Highly customizable visual logic
- Advanced interactivity (custom tooltips, logic-based filters)
- Easy to extend with new data or analytics logic

**Tableau**
- Strong default visuals
- Customization can become restrictive for advanced logic
- Less control over calculation pipelines

---

### 3. Scalability & Reproducibility
**Python (Better)**
- End-to-end reproducible pipeline
- Scales well as data size and complexity increase
- Suitable for production and automation

**Tableau**
- Excellent for exploratory analysis
- Less suitable for automated pipelines
- Reproducibility depends on manual steps

---

### 4. Ease of Use & Speed
**Tableau (Better)**
- Faster initial development
- Minimal coding required
- Ideal for quick business insights and non-technical users

**Python**
- Slightly steeper learning curve
- Requires coding and debugging

---

## Final Verdict: Which Is Better?
- **Python is better** for:
  - Advanced analytics
  - Reproducibility
  - Scalability
  - Long-term maintainability
- **Tableau is better** for:
  - Rapid prototyping
  - Business-facing dashboards
  - Non-technical stakeholder use

In this project, **Python was chosen as the primary implementation** due to its flexibility, reproducibility, and ability to support complex analytical logic. Tableau served as a complementary BI comparison.

---

Python Dashboard

## Dashboard Preview

<img src="assets/python_dashboard_preview.png" alt="Python Dashboard Preview" width="100%">

👉 Click here to open the interactive version:  
https://github.com/tus2014ar/Alzheimer-s-Market-Overview---United-States/blob/b6f8ebbbce9bc7e35e445472415fa05856f8f562/outputs/DasboardPythonFinal.html
