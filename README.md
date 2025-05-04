# EDA-WHO-Dataset  
**Exploratory Data Analysis on Global Under-5 Mortality Rates**



## 🔍 Overview  
This project explores the under-5 mortality rates worldwide using Exploratory Data Analysis (EDA) techniques in Python. The primary objective is to analyze if death rates have reduced over time due to medical advancements and identify regions and causes with the highest under-5 death rates globally. Also which factors effect the most to mortality: income, age etc.



## 📂 Dataset  
The dataset is sourced from the World Health Organization (WHO) and can be found here:  
🔗 **WHO Under-5 Mortality Dataset**



## 🛠️ Technologies & Libraries Used  
- Python (Pandas, Matplotlib, Seaborn)  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Data Visualization



## 🔄 Steps in Analysis  

### 1️⃣ Data Cleaning & Preprocessing  
Created a copy of the dataset for modifications:
- Removed unwanted columns  
- Handle missing values  
- Handle duplicate values  
- Renamed columns to avoid syntax errors  
- Feature Selection for analysis  

### 2️⃣ Exploratory Data Analysis (EDA)  
- Year-wise Trends  
- Income Group Analysis  
- Cause-wise Analysis  
- Regional Analysis  

---

## 📊 Key Findings & Insight

### 📅 Year
1. **Is there a correlation between the year and mortality rates**  
   A correlation of -0.0165 indicates a very weak, nearly negligible negative linear relationship between Year and Number of under 5 deaths  

2. **How has the number of under-5 death rates changed over the year**  
   Between 2000 to 2021, the under-five mortality rates experienced a notable decrease, dropping from 12.28 million to 7.03 million.  
   This may be due to various medical advances, vaccination coverage, and new diagnostic studies  

3. **Death Rates for Top Five Countries Over Years**  
   - China and India started with high death rates in 2000 but decreased continuously over the years, indicating a decline in mortality rates.  
   - Ethiopia: Appears relatively stable over the years, without noticeable increases or decreases in mortality rates.  
   - Nigeria: Shows a slight increase in mortality rates after 2010, indicating a potential rise in death rates during that period.  
   - Pakistan's deaths went up until about 2005, then went down a bit after 2015.  

4. **Which cause was the reason for highest death rates every year**  
   The leading cause contributing to the highest mortality rates: **Prematurity**



### 💰 Income Group
1. **Total death rates per income group overall**  
   - Among the income groups, lower middle-income shows the highest death rates compared to others, while the high-income group shows the lowest death rates.  

2. **Cause-Based Analysis Across Income Groups**  
   - After analyzing, it's clear that the lower middle-income group experiences the highest death rates compared to other income brackets.
   -  High-income group shows lower death rates.  
   - The top reasons for the highest death rates seem to be **Prematurity, birth asphyxia, and birth trauma** in the lower middle-income group.  

3. **Region-Based Analysis Across Income Groups**  
   - Europe consistently has the most high-income groups across all income levels compared to other regions.  
   - Africa having a large number of lower-middle-income groups suggests there might be a higher chance of more deaths compared to other regions.  
   - Regions like Americas, Europe, and the Western Pacific don't seem to have any low-income groups. These regions may have strong economies, influencing fewer people to fall into the low-income category.



### ⚠️ Cause
1. **Maximum mortality rates by each cause**  
   - **Prematurity** has the highest max deaths, followed by **birth asphyxia and birth trauma**.  
   - Next most common causes for max death rates are **noncommunicable (neonatal and under-5 only) diseases** and **acute lower respiratory infections**.

2. **Total death rate due to each cause throughout the years**  
   - **Prematurity** seems to be the cause of highest death rates globally



### 🌍 Region
1. **Correlating entry counts to death rates across regions**  
   - Europe: Most data (16,632 entries), lowest average death rates  
   - Americas: High number of entries, also lower average death rates  
   - South-East Asia: Less data (3,696 entries), highest average death rates  

2. **What trends do we observe in the death rates among different regions over the years?**  
   - South East Asia had the highest death rates in the initial ten years.  
   - After 2010, Africa's death rates increased compared to South East Asia.  
   - America and Europe appear consistent over the past 20 years, suggesting these regions have relatively lower and more manageable under-5 death rates.  

3. **In each year, which region registers the highest death rates among children under five?**  
   - Until 2010, South East Asia had the most deaths  
   - After that, Africa's deaths increased  

4. **Find out that which Region has which income groups**  
   - America and Europe have the most upper-middle-income compared to other regions  
   - In Africa, where the lower middle income group is highest, the under-5 death rates are also the highest among other regions  



## 📁 Repository Structure


📂 EDA-WHO-Dataset
│── 📜 WHO_Under5_Mortality.csv       # Raw Dataset  
│── 📜 EDA_WHO.ipynb                  # Jupyter Notebook with analysis  
│── 📊 Visualizations/                # Folder with generated plots  
│── 📜 README.md                      # Project Documentation  
```
