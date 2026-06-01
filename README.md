# 📊 A/B Testing Statistical Analysis for Landing Page Optimization

## 📌 Project Overview

This project analyzes a synthetic A/B testing experiment for a landing page using Python and statistical inference techniques.

The objective is to evaluate whether different versions of a web page generate statistically significant differences in:

* Conversion rates
* User spending
* Click behavior
* Device performance
* Regional behavior

The project demonstrates practical data analytics skills commonly used in:

* Product Analytics
* Marketing Analytics
* CRO (Conversion Rate Optimization)
* Business Intelligence
* Experimentation \& Hypothesis Testing

\---

## 🧠 Business Problem

A company launched two versions of a landing page:

* Version A
* Version B

The goal is to determine whether one version performs better and whether user behavior changes depending on:

* Device type
* Region
* User interaction patterns

The analysis helps stakeholders make data-driven decisions before deploying changes to production.

\---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* SciPy
* Statsmodels
* Jupyter Notebook

\---

## 📂 Project Structure

```bash
├── data/
│   ├── landing-experiment-synthetic.csv
│   ├── landing-experiment-synthetic\\\_2.csv
│   └── landing-experiment-synthetic\\\_3.csv
│
├── notebooks/
│   └── landing\\\_experiment\\\_synthetic.ipynb
│
├── README.md
└── requirements.txt
```

\---

## 📈 Statistical Techniques Applied

### 1\. Exploratory Data Analysis (EDA)

* Data inspection
* Data type classification
* Descriptive statistics
* Categorical analysis

### 2\. T-Test

Used to compare means between groups:

* Spending differences between page versions
* Click behavior by device
* Regional spending analysis

### 3\. Z-Test for Proportions

Used to compare conversion rates between groups:

* Conversion rate by page version
* Binary conversion analysis
* Conversion rate by region/device

### 4\. Chi-Square Test

Used to analyze relationships between categorical variables:

* Device vs conversion
* Region vs conversion

\---

## 📊 Example Business Insights

* One landing page version generated statistically significant differences in spending behavior.
* Desktop users showed higher interaction levels compared to mobile users.
* Certain regions achieved higher conversion rates.
* Device distribution influenced conversion outcomes.

\---

## 🚀 Proposed Improvements (Senior-Level Roadmap)

### ✅ 1. Modularize the Notebook into a Real Analytics Project

Convert notebook logic into reusable modules:

```bash
src/
├── data\\\_loader.py
├── preprocessing.py
├── statistical\\\_tests.py
├── visualization.py
└── utils.py
```

Benefits:

* Cleaner architecture
* Easier maintenance
* Better scalability
* Production-ready structure

\---

### ✅ 2. Add Professional Data Visualizations

Current project focuses strongly on statistics, but adding visual analytics would improve storytelling.

Recommended charts:

* Boxplots
* Histograms
* Conversion funnels
* Heatmaps
* Confidence interval plots
* A/B comparison dashboards

Libraries:

* Matplotlib
* Seaborn
* Plotly

\---

### ✅ 3. Add Effect Size Metrics

Statistical significance alone is not enough.

Add:

* Cohen’s d
* Relative uplift
* Absolute uplift
* Confidence intervals

This demonstrates stronger analytical maturity.

\---

### ✅ 4. Add Business Recommendations Section

Example:

> “Deploy version B for desktop traffic in northern regions because it increased conversion by X% with statistical significance.”

This transforms the notebook from:

* “Technical analysis”
into:
* “Business decision support”

Huge improvement for recruiters.

\---

### ✅ 5. Add Data Validation Layer

Include:

* Null validation
* Duplicate detection
* Type assertions
* Outlier inspection

Shows professional engineering practices.

\---

### ✅ 6. Add Reproducibility

Create:

* `requirements.txt`
* Virtual environment instructions
* Seed control for reproducibility

Example:

```python
np.random.seed(42)
```

\---

### ✅ 7. Include Executive Summary

Add a top section with:

* Objective
* Main findings
* Final recommendation
* Statistical confidence

Recruiters and managers love this.

\---

### ✅ 8. Add KPI-Oriented Thinking

Introduce metrics such as:

* Conversion Rate (CR)
* Revenue per User (RPU)
* Average Order Value (AOV)
* Click-through Rate (CTR)

This makes the project more business-oriented.

\---

### ✅ 9. Create Power BI Dashboard Version

Recommended next step:

* Build an executive dashboard in Power BI
* Include filters by:

  * Device
  * Region
  * Page version

This would massively improve your portfolio value.

\---

### ✅ 10. Publish as Portfolio Project

Recommended GitHub repository structure:

```bash
ab-testing-landing-page-analysis/
```

Suggested tags:

* data-analysis
* statistics
* ab-testing
* hypothesis-testing
* python
* pandas
* business-intelligence

\---

## 💼 Skills Demonstrated

### Technical Skills

* Statistical hypothesis testing
* Data analysis
* Exploratory data analysis
* Python data stack
* Analytical reasoning

### Business Skills

* Experiment interpretation
* KPI evaluation
* Decision-oriented analysis
* Behavioral segmentation

\---

## 📌 Future Improvements

Possible advanced versions:

* Bayesian A/B testing
* Logistic regression
* Uplift modeling
* Experiment power analysis
* Sequential testing
* Causal inference

\---

## ▶️ How to Run

### 1\. Clone the repository

```bash
git clone https://github.com/your-user/your-repository.git
```

### 2\. Install dependencies

```bash
pip install -r requirements.txt
```

### 3\. Open Jupyter Notebook

```bash
jupyter notebook
```

\---

## 👨‍💻 Author

Data Analyst Portfolio Project focused on:

* A/B Testing
* Statistical Inference
* Business Analytics
* Experimentation

\---

## ⭐ Why This Project Matters

This project demonstrates the transition from:

* Junior Analyst → statistical practitioner
toward:
* Mid-Level Analyst → business-focused experimentation analyst

It shows analytical thinking, statistical rigor, and decision-making skills valuable in modern data teams.

