# 📊 Placement Data Analysis & Visualization using Python

This project provides an in-depth analysis of a placement dataset to uncover insights about how academic performance, gender, work experience, and specialization affect student placement outcomes and salary. It combines data preprocessing, statistical exploration, correlation studies, and rich visualizations using Python.

---

## 🛠️ Tech Stack

- **Language**: Python 3
- **Libraries**: 
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scipy` (RBF interpolation for salary surface)

---

## 📂 Dataset Description

**File:** `Placement_Data_Full_Class.csv`  
Contains features such as:

- Academic performance: `ssc_p`, `hsc_p`, `degree_p`, `etest_p`, `mba_p`
- Boards: `ssc_b`, `hsc_b`
- Specialization: `specialisation`, `degree_t`
- Gender, Work Experience, Placement Status
- Salary offered

---

## 🔍 Project Workflow

### 📌 1. Data Loading and Cleaning

- Loaded CSV using `pandas`
- Inspected data types and missing values
- Replaced missing salary values with `0`
- Identified and removed salary outliers using IQR

### 📌 2. Exploratory Data Analysis (EDA)

- Descriptive statistics using `.describe()`
- Boxplots to detect outliers
- Histograms to visualize distribution of salary and scores

### 📌 3. Correlation Analysis

- Heatmap showing correlation between numerical attributes (e.g., SSC %, MBA %, salary)
- Helps identify strong relationships between scores and placement outcome

### 📌 4. Gender-wise Placement Study

- Aggregated placement counts and average salaries
- 100% stacked bar chart visualizing placement rate by gender
- Percentage annotation on plots for better interpretability

### 📌 5. SSC vs HSC vs Salary (RBF Interpolation)

- Generated smooth contour plots using Radial Basis Function
- Revealed how combinations of SSC and HSC scores influence salary

### 📌 6. Academic Scores vs Placement Rate

- Stacked bar plots for:
  - SSC percentage
  - HSC percentage
  - Degree percentage
  - MBA percentage
  - E-test scores
- Score bins grouped by 10%
- Shows how performance in each academic stage affects placement

### 📌 7. Work Experience Impact

- Bar chart showing how prior work experience affects placement rates
- Percentage distribution between "Placed" and "Not Placed"

### 📌 8. Salary by Degree and Specialization

- Tabular comparison of average salary across different degree types and specializations

---

## 📈 Visualizations

Here are some of the plots generated:

- 📦 **Boxplot** for salary distribution (before and after cleaning)
- 🔥 **Heatmap** for correlation matrix
- 🧑‍🎓 **Stacked Bar Charts** for score-based placement relation
- 🌈 **Contour Plot** showing salary surface based on SSC & HSC
- 👨‍🏫 **Work Experience Chart** showing placement advantage

---

## 💻 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/placement-analysis.git
   cd placement-analysis
