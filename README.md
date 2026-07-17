<div align="center">

# 🗽 NYC 311 Service Request Analysis

### *Uncovering patterns in 362,000+ service requests across New York City*

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

</div>

---

## 📖 About The Project

This project dives deep into **NYC's 311 service request data**, applying data wrangling, exploratory analysis, and rigorous statistical testing to uncover meaningful patterns in how the city handles citizen complaints — from noise violations to blocked driveways.

> 💡 **Key Question**: Does the *type* of complaint actually affect how fast NYC resolves it? Spoiler: Yes, and the statistics prove it.

---

## ✨ Highlights

| 📊 Metric | Value |
|:---|:---:|
| **Total Records Analyzed** | 362,177 |
| **Complaint Categories** | 23 |
| **Cities Covered** | 54+ |
| **Statistical Tests** | ANOVA + Kruskal-Wallis |
| **Date Range** | 2010 – 2026 |

---

## 🏆 Top 5 Complaint Types

<div align="center">

| Rank | Complaint Type | Count |
|:---:|:---|---:|
| 🥇 | Blocked Driveway | 100,624 |
| 🥈 | Illegal Parking | 91,716 |
| 🥉 | Noise - Street/Sidewalk | 51,139 |
| 4️⃣ | Noise - Commercial | 43,751 |
| 5️⃣ | Derelict Vehicle | 21,518 |

</div>

---

## 🔬 Statistical Findings

<table>
<tr>
<td width="50%">

### One-Way ANOVA
```
F-statistic = 565.2616
p-value     ≈ 0.0000
```
✅ **Significant**

</td>
<td width="50%">

### Kruskal-Wallis H Test
```
H-statistic = 11988.2694
p-value     ≈ 0.0000
```
✅ **Significant**

</td>
</tr>
</table>

**🎯 Conclusion:** Complaint type has a statistically significant effect on resolution time (p < 0.05). Categories like **Animal Abuse** and **Homeless Encampment** take dramatically longer to resolve than **Noise** or **Blocked Driveway** complaints.

---

## 🗺️ What's Inside

```
📦 NYC-311-Analysis
 ┣ 📓 311_analysis.ipynb    → Complete analysis notebook
 ┣ 📄 README.md             → You are here
 ┣ 📋 requirements.txt      → Python dependencies
 ┗ 🚫 .gitignore             → Ignored files
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/nayanjoshi728/NYC-311-Analysis.git
cd NYC-311-Analysis
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Launch the notebook
```bash
jupyter notebook 311_analysis.ipynb
```

---

## 🧭 Analysis Workflow

- [x] **Understand the dataset** — shape, columns, structure
- [x] **Clean & wrangle data** — handle nulls, fix date logic errors
- [x] **Engineer features** — calculate `Request_Closing_Time`
- [x] **Explore complaint patterns** — by type and by city
- [x] **Visualize geography** — scatter & hexbin plots of Brooklyn density
- [x] **Compare response times** — across complaint categories
- [x] **Test significance** — ANOVA & Kruskal-Wallis H test
- [x] **Draw conclusions** — actionable insights for city resource allocation

---

## 📈 Sample Visualizations

This notebook includes:
- 📊 Frequency plots of missing data
- 🏙️ Complaint distribution by city
- 🗺️ Brooklyn complaint density (scatter + hexbin)
- 📉 Top 10 complaint types
- ⏱️ Average response time comparisons
- 📦 Stacked bar charts across top cities & complaint types

---

## 💡 Key Insight

> Targeted resource allocation — especially for slow-resolving categories like **Animal Abuse** and **Homeless Encampment** — could meaningfully improve NYC's overall 311 service efficiency.

---

## 🛠️ Built With

- **pandas** & **numpy** — data manipulation
- **matplotlib** & **seaborn** — visualization
- **scipy** — statistical testing

---

## 📬 Connect

<div align="center">

**Nayan Joshi**

[![GitHub](https://img.shields.io/badge/GitHub-nayanjoshi728-181717?style=for-the-badge&logo=github)](https://github.com/nayanjoshi728)

</div>

---

<div align="center">

⭐ **If you found this project useful, consider giving it a star!** ⭐

</div>
