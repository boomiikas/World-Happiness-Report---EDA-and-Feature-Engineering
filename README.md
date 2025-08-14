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
- plus engineered features like:
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

Extra Analysis on World Happiness Dataset

This section provides deeper insights and observations from the dataset beyond the mandatory analysis.

### Key Insights

1. **Happiness Gap Within Regions**
   - Regions with **higher standard deviation** in Ladder Score indicate a **larger happiness gap** between countries in the same region.
   - Some regions contain **rich but less happy countries** or **poor but happier countries**.
   - Boxplots reveal **outliers** in happiness scores, highlighting exceptional countries.

2. **Happiness and Governance**
   - Countries with **lower perceptions of corruption** tend to be **happier**.
   - This shows that **good governance and transparency** positively impact happiness levels.

3. **Freedom and Happiness**
   - Countries where people enjoy **higher freedom to make life choices** tend to have **higher Ladder Scores**.
   - Suggests personal autonomy is an important contributor to happiness.

4. **Correlation with Socioeconomic Factors**
   - Ladder Score is **highly positively correlated** with:
     - **GDP per capita**
     - **Social support**
     - **Healthy life expectancy**
   - Indicates that **wealth, social networks, and health** are strong drivers of happiness.
   - **Perceptions of corruption** tend to have a **negative correlation**, reinforcing the impact of governance on happiness.

5. **Visual Trends**
   - Average happiness by region highlights **regional differences** in wellbeing.
   - Scatter plots of GDP vs Ladder Score reveal countries that **deviate from expected trends** (rich but unhappy or poor but happy).

These extra insights provide a deeper understanding of the **drivers of happiness**, **regional disparities**, and **governance effects** beyond basic averages.
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
