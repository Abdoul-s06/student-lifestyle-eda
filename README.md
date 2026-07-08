# Student Lifestyle EDA

**Exploring the lifestyle costs of academic performance**

An exploratory data analysis of university student survey data, examining how sleep, study hours, physical activity, and stress relate to CGPA.

**Author:** Abdoul Salma  
**Tools:** Python · pandas · seaborn · matplotlib

---

## Overview

University students often face a tension between academic performance and personal well-being. This project investigates a central question: **do students who trade sleep for study time achieve better GPAs—and at what cost to their stress levels?**

Using self-reported survey data from students (primarily in India, collected August 2023–May 2024), the analysis maps relationships between daily habits and academic outcomes through data cleaning, grouped summaries, and visual comparisons.

## Key Findings

- **Study hours, not sleep, showed the strongest association with CGPA.** Sleep duration had little linear relationship with grades.
- **38.8% of students reported fewer than 7 hours of sleep**, below the commonly recommended 7–9 hour range.
- **Students sleeping less than 7 hours reported higher average stress** than those in the 7–9 hour range.
- **Top CGPA students showed the highest stress profile** — studying the most, sleeping less, and reporting mean stress of 2.94 (on a 1–3 scale).
- **Physical activity was associated with lower stress** — average stress decreased from 2.63 (0–2 hrs of activity) to 2.21 (5+ hrs).

## Project Structure

```
.
├── README.md
├── Student_Lifestyle.ipynb    # Full analysis notebook
└── Daily_Lifestyle_and_Academic_Performance.csv   # Dataset (download separately)
```

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab

### Installation

```bash
pip install pandas matplotlib seaborn jupyter
```

### Dataset

Download the dataset from Kaggle and place it in the project root:

**[Daily Lifestyle and Academic Performance of Students](https://www.kaggle.com/datasets/steve1215rogg/student-lifestyle-dataset/data)**

The notebook expects the file to be named:

```
Daily_Lifestyle_and_Academic_Performance.csv
```

### Run the Analysis

```bash
jupyter notebook Student_Lifestyle.ipynb
```

Run all cells from top to bottom. The notebook covers data preparation, exploratory analysis, and a written summary of findings.

## Analysis Highlights

| Topic | Approach |
|---|---|
| Stress distribution | Bar chart of reported stress levels |
| Sleep patterns | Histogram and sleep-group breakdowns |
| Sleep vs. CGPA | Scatter plot |
| Study hours vs. CGPA | Scatter plot |
| Stress by lifestyle factors | Box plots, grouped averages by CGPA tier and sleep group |
| Physical activity vs. stress | Binned activity groups with mean stress |

## Limitations

- All variables are **self-reported** survey responses.
- The sample is **geographically concentrated** (primarily India).
- Findings describe **associations**, not causation.

## Data Source

[Rogge, S. — Student Lifestyle Dataset (Kaggle)](https://www.kaggle.com/datasets/steve1215rogg/student-lifestyle-dataset/data)

## License

This project is for portfolio and educational use. The underlying dataset is subject to Kaggle's terms of use.
