# 🚢 Titanic Dataset Analysis

This project performs a complete Exploratory Data Analysis (EDA) on the Titanic dataset to understand which factors influenced passenger survival. The analysis includes data cleaning, handling missing values, feature engineering, and visualizations to highlight survival trends across different passenger groups.

---

## 📁 Project Overview
The goal of this project is to explore the Titanic dataset and uncover meaningful insights related to:
- Passenger demographics  
- Travel class and ticket details  
- Family size and relationships  
- Key factors impacting survival probability  

Your notebook includes both data preprocessing and visualization-driven analysis to build a clear understanding of the patterns within the dataset.

---

## 🛠️ Tools & Libraries Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 🔧 Data Cleaning & Preprocessing
The project includes:
- Handling missing values (`Age` filled using median, `Cabin` column dropped due to sparsity).
- Cleaning categorical values like `Embarked`.
- Converting data types where required.
- Removing duplicates.
- Standardizing column formats.

---

## 🧪 Feature Engineering
You created additional features to improve analysis:
- **FamilySize** = SibSp + Parch + 1  
- **isAlone** (passenger traveling without family)  
- **Title Extraction** from passenger names  

These features help reveal hidden survival patterns.

---

## 📊 Exploratory Data Analysis
The notebook includes visual analysis of:
- Survival count and percentage  
- Gender vs Survival  
- Passenger Class (Pclass) vs Survival  
- Age distribution & Age group survival  
- Family size impact  
- Embarkation point comparison  
- Correlation heatmap  

Multiple bar charts, histograms, countplots, and boxplots are used to show relationships clearly.

---

## 🔍 Key Insights
- Females had significantly higher survival rates than males.  
- First-class passengers survived more compared to lower classes.  
- Young children showed higher survival probabilities.  
- Passengers traveling alone had lower survival rates.  
- Embarkation point influenced survival distributions.  

---


