# A/B Testing & Experiment Analysis (Python)

## 📌 Project Overview
This project analyzes an A/B experiment conducted to evaluate the impact
of a new checkout experience on user conversion and revenue.

The objective is to determine whether the treatment group (new checkout)
outperforms the control group (existing checkout) using statistical testing
and business-focused analysis.

---

## 📊 Dataset Description
The dataset simulates real-world experimental data and includes:
- User group assignment (Control vs Treatment)
- Conversion indicator
- Revenue per user
- Device type
- Session duration

---

## 🔍 Analysis Workflow

### 1. Experiment Design & Hypothesis Definition
- Defined control and treatment groups
- Established null and alternative hypotheses

### 2. Data Validation & Sanity Checks
- Verified balanced group sizes
- Checked randomization across devices
- Ensured consistent data integrity

### 3. Exploratory Data Analysis (EDA)
- Conversion rate comparison
- Revenue per user analysis
- Device-level conversion patterns
- Behavioral insights using session duration

### 4. Statistical Testing
- Two-sample proportion z-test for conversion rates
- Welch’s t-test for mean revenue comparison
- Mann–Whitney U test for robust revenue validation

### 5. Revenue Impact Analysis
- Evaluated revenue per user uplift
- Confirmed statistical significance under skewed distributions

---

## 📈 Key Insights
- The treatment group showed higher conversion rates than control.
- Revenue per user was significantly higher for the treatment group.
- Results were consistent across multiple statistical methods.

---

## ✅ Final Recommendation
The new checkout experience should be rolled out to all users, as it delivers
statistically significant improvements in both conversion and revenue.

---

## 🛠 Tools & Libraries Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- SciPy, Statsmodels
- Google Colab

---

## 📁 Deliverables
- Statistical test results
- Visual analysis of conversion and revenue
- Business-ready recommendation and risk assessment

---

## 🚀 Next Steps
- Segment-level analysis (device, country)
- Long-term impact monitoring
- Additional experiments on pricing or UX optimization


