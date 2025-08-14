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
## 📈 Extra Analyses

Extra Analysis on World Happiness Dataset

### Key Insights

1. **Happiness Gap Within Regions**
   - Regions with **higher standard deviation** in Ladder Score indicate a **larger happiness gap** between countries in the same region.
   - Some regions contain **rich but less happy countries** or **poor but happier countries**.
   - Boxplots reveal **outliers** in happiness scores, highlighting exceptional countries.
     ### Key Insights

1. **Happiness Gap Within Regions**
   - Regions with **higher standard deviation** in Ladder Score have a **larger happiness gap** between countries.
   - Some regions include **rich but less happy** or **poor but happier countries**.
   - Boxplots show **outliers**, highlighting exceptional cases.
   <img width="974" height="869" alt="image" src="https://github.com/user-attachments/assets/993d01ec-afd5-49e6-910a-536bddfcbee6" />

2. **Governance and Corruption**
   - Countries with **lower corruption perception** tend to be **happier**, showing the impact of **good governance**.
     <img width="685" height="545" alt="image" src="https://github.com/user-attachments/assets/2ec68b00-c865-4f35-a45f-37e66246df6e" />


3. **Freedom**
   - Higher **freedom to make life choices** correlates with **higher happiness**, emphasizing personal autonomy.
     <img width="678" height="545" alt="image" src="https://github.com/user-attachments/assets/57282f06-d646-4406-89eb-555d9f82fbb4" />


4. **Socioeconomic Factors**
   - Ladder Score positively correlates with **GDP per capita, social support, and life expectancy**.
   - **Corruption perception** has a negative correlation, reinforcing governance effects.
     <img width="988" height="799" alt="image" src="https://github.com/user-attachments/assets/1930c992-6536-46e7-8d5c-92014b16f2db" />


5. **Visual Trends**
   - Average happiness by region shows **regional differences**.
   - GDP vs Ladder Score plots reveal **countries deviating from expected trends** (rich but unhappy or poor but happy).
     <img width="988" height="799" alt="image" src="https://github.com/user-attachments/assets/2425f42a-b455-4a89-aa99-7881aad9f7f2" />

---

## 🛠️ Tech Stack
- **Python**: Data processing & analysis
- **Pandas, NumPy**: Data manipulation
- **Matplotlib, Seaborn**: Visualization
- **Scikit-learn**: Modeling
- **SymPy**: Calculus operations

---

## 📊 Key Findings 
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
