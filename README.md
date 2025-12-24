# EDA_INTERNSHIP

Here is a professional, comprehensive `README.md` file tailored for your project. It highlights the data cleaning rigor and the strategic value of the visualizations you created.

---

# Global Logistics Optimization: A Data-Driven Performance Audit

## 📌 Project Overview

This project focuses on transforming raw, "dirty" supply chain data into a high-fidelity analytical asset. By implementing a robust data cleaning pipeline and advanced visualizations, we identify systemic bottlenecks, freight cost inefficiencies, and delivery performance trends.

The goal is to provide stakeholders with actionable insights to reduce **Delivery Delays** and optimize **Freight Cost ROI**.

---

## 🛠️ Data Cleaning Pipeline

The raw dataset initially contained over 1,700 missing values and several data type inconsistencies. Our cleaning process ensures 100% data integrity:

* **Deduplication:** Removal of redundant records to prevent skewed metrics.
* **Global Null Handling:** Categorical gaps resolved as "Unknown"; numeric gaps filled via median imputation.
* **Explicit Date Parsing:** Standardized ISO formats to eliminate parsing warnings and ensure accurate lead-time calculations.
* **Outlier Mitigation:** Purged "impossible" data points (e.g., negative weights or year-long delays) using statistical clipping.
* **Memory Optimization:** Implementation of `category` dtypes for high-cardinality strings.

---

## 📊 Key Visualizations & Insights

### 1. Shipment Punctuality Distribution

* **Visual:** Distribution Histogram with KDE.
* **Insight:** Identified a "Late-Tail" risk, proving that shipments are statistically more likely to be delayed than delivered early.

### 2. Freight Cost vs. Weight Efficiency

* **Visual:** Log-Log Scatter Plot.
* **Insight:** Mapped the economic logic of the supply chain, identifying "Efficiency Leaks" where premium prices were paid for standard weights.

### 3. Transport Method Mix by Category

* **Visual:** Normalized Stacked Bar Chart.
* **Insight:** Verified strategic alignment by ensuring high-priority health products utilize faster "Air" transport modes.

### 4. Performance Scorecard by Mode

* **Visual:** Ranked Horizontal Bar Chart.
* **Insight:** Pinpointed specific transport bottlenecks, providing a data-driven basis for vendor accountability and contract renegotiation.

---

## 🚀 Business Impact

* **Positive Growth:** Potential to reduce overhead by 5-10% through optimized mode-shifting.
* **Risk Mitigation:** Early detection of "Systemic Transit Lag" prevents long-term customer dissatisfaction and prevents negative growth trends.

---

## 💻 Installation & Usage

1. **Clone the repository:**
```bash
```


2. **Install dependencies:**
```bash
!pip install pandas numpy matplotlib seaborn

```


3. **Run the analysis:**
Open the Jupyter Notebook and execute the cells to see the cleaning pipeline and generated charts.

---

## 📂 Project Structure

```text
├── data/
│   └── raw_logistics_data.csv    # Original dataset
├── notebooks/
│   └── cleaning_analysis.ipynb   # Main cleaning & Viz code
├── outputs/
│   └── final_report_charts/      # Exported high-res visuals
└── README.md

```

Would you like me to help you write the **"How to Contribute"** or **"License"** sections to make this a truly complete GitHub repository?
