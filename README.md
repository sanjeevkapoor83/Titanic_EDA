# Titanic Dataset - Exploratory Data Analysis (EDA)


## 📌 Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset to identify key patterns, trends, and factors influencing passenger survival.  
The analysis includes both **statistical exploration** and **visualizations** using Python.

## 📂 Files in This Repository
- **`titanic_eda.py`** → Python code for the complete EDA process.  
- **`new file titanic.csv`** → Titanic dataset used for the analysis.  
- **`Titanic_EDA_Report.pdf`** → Final report containing graphs and detailed observations.  


## 🔍 Steps Performed
1. **Data Loading & Inspection**  
   - Checked dataset shape, data types, and missing values.  
   - Generated summary statistics for numerical and categorical columns.  

2. **Univariate Analysis**  
   - Distribution plots for numerical columns (Age, Fare, etc.).  
   - Count plots for categorical columns (Sex, Pclass, Embarked).  

3. **Bivariate Analysis**  
   - Relationship between survival and gender, passenger class, and age.  
   - Boxplots, countplots, and survival rate comparisons.  

4. **Correlation Analysis**  
   - Heatmap to find correlations among numerical features.  
   - Identified strong negative correlation between Fare and Pclass.  

5. **Pairplot Visualization**  
   - Multi-variable comparison between survival and other attributes.  


## 📊 Key Insights
- Female passengers had a **much higher survival rate** (~74%) compared to males (~19%).  
- **First-class passengers** had the highest survival (~63%), while third-class had the lowest (~24%).  
- Higher fares were generally linked to **better survival chances**.  
- **Age** had only a minor impact on survival.  
- **Cabin** column had significant missing data and needs special handling.  


## 🛠 Tools & Libraries Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- PyCharm IDE  

## 📜 Conclusion
The EDA revealed that **gender** and **passenger class** were the most influential factors in determining survival.  
This project demonstrates how data visualization and statistical exploration can uncover hidden patterns in datasets.



