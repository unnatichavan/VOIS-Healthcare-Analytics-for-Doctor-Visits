# VOIS TIRTC DIY Project – Healthcare Analytics for Doctor Visits

### Doctor Visit Analysis using Python

**Submitted by:** Unnati Dinesh Chavan  
**Course:** B.E. Artificial Intelligence & Data Science  
**College:** Terna Engineering College, Nerul  
**Batch:** VOIS AICTE 2026–2027

---

## 📌 Project Overview

This project involves a comprehensive analysis of a healthcare dataset containing 5,190 patient records. The goal is to identify patterns in hospital visits and understand what factors influence healthcare utilization.

---

## 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| **Source** | VOIS TIRTC Program |
| **Rows** | 5,190 |
| **Columns** | 12 |
| **Target Variable** | `visits` |

### Column Description

| Column | Description |
|--------|-------------|
| `visits` | Number of hospital visits |
| `gender` | Male / Female |
| `age` | Age factor |
| `income` | Income factor |
| `illness` | Number of illnesses |
| `reduced` | Reduced activity days |
| `health` | Self-reported health score |
| `private` | Private insurance (yes/no) |
| `freepoor` | Free care for poor (yes/no) |
| `freerepat` | Free care for repeat visits (yes/no) |
| `nchronic` | Number of chronic conditions |
| `lchronic` | Limited chronic conditions |

---

## 🔍 Analysis Performed

- Data loading and inspection
- Missing value detection
- Distribution analysis (illness, gender, income)
- Correlation heatmap
- Income vs visits (scatter plot)
- Gender count plot
- Insurance coverage analysis (pie charts)
- Reduced activity by gender (bar chart)

---

## 📈 Key Insights

- Illness severity strongly correlates with reduced activity days
- Income does not significantly influence hospital visits
- Around 55% of patients have private insurance
- Males show slightly more reduced activity days than females
- The dataset is well-balanced between genders

---

## 🛠️ Technologies Used

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook (Google Colab)
- GitHub, VS Code

---

## 📂 Repository Structure
VOIS-Healthcare-Analytics-for-Doctor-Visits/
├── Healthcare_Analytics_for_Doctor_Visits.ipynb
├── 1776250375-P2-Healthcare Analytics for Doctor Visits.csv
└── README.md


---

## 🚀 How to Run

1. Open the `.ipynb` file in Google Colab
2. Upload `DoctorVisits.csv`
3. Run all cells sequentially

---


**VOIS AICTE Batch 2026–2027**  
📍 Completed by **Unnati Chavan**