# 🌍 World Happiness Report 2024 – Data Analysis

## 📌 Project Overview
This project analyzes the **World Happiness Report 2024** dataset from [Kaggle](https://www.kaggle.com/datasets/jainaru/world-happiness-report-2024-yearly-updated) using **Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)**.

We explore global and regional happiness patterns, identify key factors influencing happiness, and perform both **descriptive** and **predictive** analyses.

---

## 📂 Dataset
**Columns include:**
- `Country name`
- `Regional indicator`
- `Ladder score` *(Happiness score)*
- `Log GDP per capita`
- `Social support`
- `Healthy life expectancy`
- `Freedom to make life choices`
- `Generosity`
- `Perceptions of corruption`
- ... plus engineered features like:
  - `is_happy`
  - `happiness_rank`
  - `above_average_gdp`
  - `life_expectancy_quartile`

**Source:** Kaggle – World Happiness Report 2024 (Yearly Updated)

---

## 🔍 Mandatory Analysis

### **Part 1 – Basic Data Understanding**
- Load dataset, display first 10 rows.
- Check shape, column names, and data types.
- Identify missing values & duplicates.
- Summary statistics with `.describe()`.
- Count unique countries & regions.
- Find happiest country & most common region.

### **Part 2 – EDA (Exploratory Data Analysis)**
- Histogram of happiness scores.
- Top 10 & bottom 10 countries by happiness.
- Average happiness score per region (bar chart).
- GDP vs Happiness (scatter plot).
- Happiness score distribution by region (boxplot).

### **Part 3 – Statistics**
- Mean, median, mode, variance, and std dev of happiness.
- % of countries below global average.
- Most common region in top 20 happiest countries.

### **Part 4 – Linear Algebra & NumPy**
- Create arrays & perform vector operations.
- Dot product of GDP and happiness arrays.
- Weighted sum of `[GDP, Social support]` using `[0.5, 0.5]`.
- Normalize happiness scores.

### **Part 5 – Calculus**
- Given:  
  `Wellbeing_Index = (GDP × Happiness) + 0.5 × (Happiness − 5)^2`  
  Find derivative wrt Happiness.

### **Part 6 – Feature Engineering**
- `is_happy` (1 if score > 7 else 0).
- `happiness_rank` (descending).
- `above_average_gdp` (1 if above global mean GDP).
- `life_expectancy_quartile` (quartiles from life expectancy).

### **Part 7 – SQL Simulation in Pandas**
- Countries with happiness > 7.
- Sort by GDP per capita descending.
- Group by region and find average happiness.
- Top 5 regions by average happiness.
- Countries with life expectancy > 70.

### **Part 8 – Insights**
- Happiest country.
- Happiest region on average.
- GDP–Happiness correlation.
- Do richer countries always have higher happiness?
- Region with highest average life expectancy.

---

## 📈 Extra Analyses

### **1. Correlation Heatmap**
Identify strongest positive & negative correlations.

### **2. Freedom & Corruption vs Happiness**
Scatter plots to see relationships with happiness.

### **3. Outlier Analysis**
Find *rich but unhappy* and *poor but happy* countries.

### **4. Multiple Regression Prediction**
Predict happiness score from GDP, life expectancy, and other factors.

### **5. Happiness Inequality by Region**
Measure variation in happiness scores (standard deviation).

### **6. Feature Importance (Random Forest)**
Rank features by predictive power.

### **7. Happiness Efficiency Metric**
Happiness per GDP unit – countries that achieve more happiness with less wealth.

---

## 🛠️ Tech Stack
- **Python**: Data processing & analysis
- **Pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn**: Visualization
- **Scikit-learn**: Modeling
- **SymPy**: Calculus operations

---

## 📊 Key Findings (Example)
- **Finland** is the happiest country in 2024.
- **Western Europe** is the happiest region on average.
- GDP per capita correlates strongly with happiness (~0.78), but some countries achieve high happiness despite lower GDP.
- Freedom, social support, and life expectancy are also key drivers.
- **Sub-Saharan Africa** shows the highest variation in happiness scores within a region.

---

## 🚀 How to Run
1. Download the dataset from Kaggle.
2. Place it in the project folder as `world_happiness_2024.csv`.
3. Run `analysis.ipynb` in Jupyter Notebook or Google Colab.
4. Explore charts and insights.

---

## 📌 Future Work
- Time-series analysis with multi-year data.
- Predict future happiness rankings.
- Incorporate climate, education, and political stability data.

---

**Author:** *BOOMIKA S*  
**Date:** 2025-08-13
