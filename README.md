# A/B Testing & Statistical Significance Analysis

## 📋 Project Description

This project is an automated A/B testing and statistical significance analysis tool designed to evaluate experiment performance and conversion metrics.

Developed in Python using Jupyter Notebook, the project automates the calculation of conversion rates, performs statistical hypothesis testing, validates sample quality, and generates segmented insights across multiple business dimensions.

The exported results are ready for further visualization and business reporting in Tableau.

---

## 🎯 Project Objectives

The main goals of this project are to:

* Automate A/B testing analysis;
* Calculate key conversion metrics;
* Compare control and test groups;
* Perform statistical significance testing;
* Validate sample size and data quality;
* Analyze experiment results across different customer segments;
* Export analytical results for business visualization.

---

## 🛠️ Technology Stack

* **Python 3.x** – primary programming language;
* **Jupyter Notebook** – interactive analysis environment;
* **Google Colab** – cloud notebook execution;
* **Pandas** – data manipulation;
* **NumPy** – numerical computations;
* **Statsmodels** – statistical hypothesis testing;
* **CSV Export** – result integration with Tableau.

---

## 📂 Project Structure

```text
A-B-Testing-Analysis/
├── README.md
├── Significance_tools.ipynb
└── AB_testing_tool.csv
```

---

## 📊 Data Source

The analysis uses experimental data stored in:

**Portfolio_Project_2.csv**

The dataset contains information about:

* User sessions;
* Experiment groups;
* Customer events;
* Device types;
* Countries;
* Continents;
* Marketing channels.

---

## 📈 Key Metrics

The project calculates several conversion metrics:

| Metric                        | Description                                |
| ----------------------------- | ------------------------------------------ |
| add_payment_info_per_session  | Payment information additions per session  |
| add_shipping_info_per_session | Shipping information additions per session |
| begin_checkout_per_session    | Checkout initiations per session           |
| new_accounts_per_session      | New account registrations per session      |
| conversion_orders_per_session | Orders per session                         |
| add_to_cart_per_session       | Add-to-cart actions per session            |

---

## ❓ Business Questions

This project aims to answer the following questions:

* Does the test group outperform the control group?
* Are observed differences statistically significant?
* Which customer segments respond differently?
* Which devices or countries show the highest uplift?
* Are experiment samples large enough for reliable conclusions?
* Which business metrics improve under the experiment?

---

## 📊 Analysis Workflow

### 1. Data Preparation

* Load experimental data;
* Configure conversion metrics;
* Prepare control and test groups.

---

### 2. Metric Calculation

Calculate conversion rates for:

* Control group;
* Test group.

---

### 3. Statistical Testing

Perform a two-proportion Z-test to compare conversion rates.

The project calculates:

* Z-statistic;
* P-value;
* Statistical significance.

---

### 4. Sample Validation

Validate experiment quality by checking:

* Minimum sample size;
* Minimum number of successful events;
* Data consistency.

---

### 5. Segmentation Analysis

The analysis is performed across multiple business dimensions:

* Device;
* Country;
* Continent;
* Marketing channel.

---

### 6. Result Export

Export the analytical results into CSV format for Tableau dashboards and business reporting.

---

## 🔬 Statistical Methods

### Two-Proportion Z-Test

The project compares conversion rates between control and test groups.

Rules:

* Significance level: **α = 0.05**;
* p-value < 0.05 indicates statistical significance;
* Minimum sample size: 100 observations;
* Minimum successful events: 5.

---

## 📊 Output Metrics

The exported dataset includes:

* Control conversion rate;
* Test conversion rate;
* Percentage uplift;
* Z-statistic;
* P-value;
* Statistical significance flag;
* Sample validation flag;
* Segment type;
* Segment value.

---

## 💡 Key Insights

The analysis helps identify:

* Winning experiment variants;
* High-performing customer segments;
* Conversion improvements;
* Regional differences;
* Device-specific behavior;
* Marketing channel effectiveness.

---

## 🚀 Business Value

The results can help businesses:

* Make data-driven product decisions;
* Optimize conversion funnels;
* Evaluate marketing experiments;
* Identify profitable customer segments;
* Reduce decision-making risk through statistical validation;
* Build Tableau dashboards for experiment monitoring.

---

## 🎓 Skills Demonstrated

This project showcases practical experience in:

* A/B testing;
* Statistical hypothesis testing;
* Two-proportion Z-tests;
* Conversion rate analysis;
* Sample validation;
* Customer segmentation;
* Python programming;
* Pandas;
* Statsmodels;
* Business analytics;
* Data storytelling;
* Tableau integration.

---

## 📌 Conclusion

A/B Testing & Statistical Significance Analysis demonstrates a complete experimental analytics workflow. The project combines automated metric calculation, statistical hypothesis testing, customer segmentation, and business reporting to support evidence-based decision-making and optimization of business performance.
