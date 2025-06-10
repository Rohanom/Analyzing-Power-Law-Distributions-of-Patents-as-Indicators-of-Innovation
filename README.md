# 📊 Patent Trend Analysis in India

A data-driven research project aimed at uncovering trends, growth patterns, and inequality in patent activity across various technology and industry domains in India. This analysis leverages statistical modeling and data visualization techniques to provide actionable insights for innovation policy, R&D strategy, and IP management.

---

## 📁 Project Overview

**Project Title:** Patent Trend Analysis  
**Course:** Design Credit Project  
**Guide:** Dr. Seema Saini  
**Team Members:**  
- Om Aditya (B23MT1028)  
- Adithyan (B23MT1005)

---

## 🎯 Objective

To analyze Indian patent data (1990–2025) across multiple sectors and domains using statistical tools and distribution models to detect:
- Innovation growth trends
- Sector dominance
- Citation inequalities
- Fit of empirical data to statistical distributions (Lognormal, Power Law, Pareto)

---

## 📌 Key Features

- 📈 Year-wise trend analysis of patent filings and grants  
- 🔍 Domain-specific insights across 50+ industries and tech sub-domains  
- 🧮 Statistical modeling of patent citation data using:
  - Empirical distributions
  - Lognormal distributions
  - Power-law distributions
  - Pareto analysis  
- 📊 Visualizations for forward and backward citations
- 💡 Policy and strategy recommendations for R&D and IP focus

---

## 🧰 Tools & Libraries

- **Python** – Data analysis and visualization  
- **Libraries**: 
  - `pandas`, `numpy` – data manipulation  
  - `matplotlib`, `seaborn` – visualizations  
  - `scipy`, `powerlaw` – statistical distribution fitting  
- **Data Source**: Extracted via PatSeer  
- [🔗 Datasets (Google Drive)](https://drive.google.com/drive/folders/10KDvaBPdrXGA6lWnkR8IHnEbC6z0kAFY?usp=sharing)

---

## 📊 Datasets Used

- Patent filings and grants (1990–2025)
- Tech domains and sub-domains
- Industry-wise patent activity
- Forward and backward citation counts

---

## 📈 Observations & Insights

### 🔹 Temporal Trends

- 🚀 Post-2020: Sharp surge in patent filings across AI, Communication, Pharma  
- 📉 2025 drop is due to incomplete data (as of April 2025)

### 🔹 Industry Dominance

- Top 5 industries (e.g., Communication Equipment, Pharma) account for ~65% of total patents  
- Computer Technology saw 517× increase in filings from 1990 to 2024

### 🔹 Citation Inequality

- A few patents (e.g., key pharmaceutical patents) dominate total citations  
- Majority of patents receive minimal citations (long-tail distribution)

---

## 📊 Distribution Analysis

| Distribution | Best Use | Fit Quality |
|--------------|----------|-------------|
| **Empirical** | Visual trends | High |
| **Lognormal** | Mid-range estimation | Poor for heavy tails |
| **Power Law** | High-impact outliers | Best fit |
| **Pareto** | Inequality measurement | Strong (80/20 behavior) |

---

## 📌 Policy Recommendations

- 🎯 Focus R&D on high-growth domains: AI, Pharma, Digital Communication  
- ⚖️ Incentivize underrepresented sectors: Agriculture, Environmental Tech  
- 📉 Address citation inequality by supporting emerging innovations  
- 🌐 Monitor global trends and geopolitical dominance (e.g., China in Comm. Tech)

---

## 📚 Mathematical Basis

- **Lognormal Distribution** – Suitable for multiplicative, moderately skewed data  
- **Pareto Distribution** – Ideal for modeling extreme inequality  
- **Power Law** – Best fit for citation and patent concentration with heavy tails

---

## 🔮 Conclusion

- Patent activity in India has surged since 2020, driven by technological breakthroughs and digitization.
- Power law models outperform others in capturing innovation inequality and high-impact behavior.
- The top 20% of sectors and patents contribute to ~80% of innovation and citations (Pareto Principle).
- This research provides actionable insights for shaping future innovation policies, R&D investment strategies, and intellectual property frameworks.

---


> 📎 Note: The 2025 data is partial and will be updated post-year-end for more accurate analysis.
