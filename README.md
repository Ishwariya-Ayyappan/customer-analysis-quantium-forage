# 🧠 Customer Analysis – Quantium Forage Project

## 📋 Overview

A data-driven analysis of supermarket chip purchases as part of the Quantium Virtual Experience on Forage. Focuses on customer segmentation, store layout experimentation, and commercial recommendations.

---

## 🔎 Table of Contents

* [Project Scope](#project-scope)
* [Data & Dependencies](#data--dependencies)
* [Analysis Workflow](#analysis-workflow)

  * Task 1: Customer Analytics
  * Task 2: Experiment & Uplift Testing
  * Task 3: Strategic Reporting
* [Key Insights & Recommendations](#key-insights--recommendations)
* [How to Run](#how-to-run)
* [Future Work](#future-work)

---

## 🗂️ Project Scope

* **Task 1**: Clean and prep purchase data; segment customers by lifestage and member type; identify brand and pack-size preferences.
* **Task 2**: Choose control stores and conduct uplift testing for stores 77, 86, 88 using sales and customer count metrics.
* **Task 3**: Synthesize findings into a client-facing presentation structured around the Pyramid Principle.

---

## 📊 Data & Dependencies

**Data Files**

* `QVI_purchase_behaviour.csv`, `QVI_transaction_data.xlsx`, `QVI_data.csv`

**Tech Stack**

* Python 3.x, Jupyter Notebooks
* Core libraries: pandas, numpy, matplotlib, seaborn, scipy, sklearn (optional)

---

## 📈 Analysis Workflow

### Task 1: Customer Analytics

* Cleaned date formats, removed non-chips items & outliers
* Segmented: lifestage and member type
* Analyzed metrics like sales per customer, pack size, brand popularity

### Task 2: Experiment & Uplift Testing

* Identified control stores via Pearson correlation and magnitude distance
* Tested statistical significance of trial effects during Feb–Apr 2019

### Task 3: Strategic Reporting

* Converted analysis into concise, client-ready PowerPoint using Pyramid Principle

---

## 🔑 Key Insights & Recommendations

* **Top segments**: Older families (budget), young singles/couples (mainstream), mainstream retirees
* **Buying behaviors**: Older families buy more units per visit; singles/couples favor Kettle and 175 g packs
* **Store trials**: Stores 77 & 86 showed significant sales/footfall increases; store 88 did not
* **Strategic takeaways**:

  1. Segment-targeted promotions (e.g., Doritos bundles for young mainstream)
  2. Expand trial layout based on Stores 77 & 86; investigate why 88 underperformed
  3. Leverage dominant brands/sizes (e.g., Kettle 150–175 g) in merchandising

---

