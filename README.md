# Decoding Customer Value: A SQL-Driven Retention Strategy

**Consulting & Analytics Club | IIT Guwahati — Summer Projects '26**

## 📌 Project Overview
This project analyzes a D2C fashion brand with ~3,900 customers to answer a critical strategic question: *Is the brand building genuine customer loyalty, or is it sustaining revenue through continuous promotional discounting?* Through data cleaning, feature engineering, and SQL-based cohort analysis, we discovered that **loyalty is being purchased, not built.** Our most "loyal" customers are actually more dependent on promo codes (46.1%) than standard buyers (42.4%), with zero spend premium per transaction. This project provides a data-backed "Promotional Sunset" roadmap and an Ideal Customer Profile (ICP) acquisition strategy to recover margin and drive true organic retention.

## 📂 Repository Structure

```text
📦 Decoding-Customer-Value
├── 📄 Dataset.csv                            # Raw D2C customer dataset (3,900 rows)
├── 📄 cleaned_dataset.csv                    # Processed dataset with engineered loyalty segments
├── 📄 Project.ipynb                          # Python EDA, Feature Engineering, & SQL Analysis
├── 📄 founder dashboard.pbix                  # Power BI Dashboard (visualizing SQL metrics)
├── 📄 Executive_Summary.pdf                 # 1-page high-level strategic brief for judges/founders
├── 📄 Playbook.pdf                          # Operational guide for the 3-phase promotional sunset
└── 📄 README.md                              # Project documentation (You are here)
```

## 🛠️ Tech Stack & Methodology
* **Data Cleaning & EDA:** Python (Pandas, NumPy, Matplotlib, Seaborn)
* **Data Modeling & Segmentation:** Python (Advanced feature engineering based on business logic)
* **Analytics:** SQL (SQLite in-memory processing for cohort, demographic, and geographic analysis)
* **Visualization:** Power BI (Interactive dashboarding for stakeholder presentation)
* **Strategy Formulation:** Management Consulting frameworks (Risk assessment, Phased rollouts, ICP targeting)

## 📊 Key Findings
1. **No Spend Premium:** "Loyal" customers spend an average of **$59.64** vs. **$59.79** for Standard customers. 
2. **High Promo Dependency:** **46.1%** of Loyal customers use discounts, indicating a habitual reliance on price cuts rather than brand affinity.
3. **The Organic Advocate (ICP):** The most profitable cohort consists of users aged **37-52** buying **Clothing**, paying via **Credit Card**, and utilizing **Next Day Air** shipping (Avg Spend: **$75.67** — a ~26% premium over baseline).

## 🚀 Strategic Recommendations
* **Promotional Sunset:** A 3-phase rollout to safely stop discounting the ~299 Loyal-Promo Dependent customers, replacing price cuts with non-price incentives (e.g., free express shipping).
* **Targeted Acquisition:** Shift marketing spend toward the older, high-margin demographic that buys without promotional triggers.
* **Retention Benchmarking:** Use the "Organic Advocate" segment (high tenure, >4.0 rating, zero promo dependency) as the gold standard for future retention KPIs.

## ✍️ Authors
* **Yash Tamboli** | Roll No: `250121066`
  *Undergraduate Student, Engineering Physics @ IIT Guwahati*

* **Yuvraj Saikia** | Roll No: `250121068`
  *Undergraduate Student, Engineering Physics @ IIT Guwahati*