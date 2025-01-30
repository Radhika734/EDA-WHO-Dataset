EDA-WHO-Dataset
📊 Exploratory Data Analysis on Global Under-5 Mortality Rates

🔍 Overview
This project explores the under-5 mortality rates worldwide using Exploratory Data Analysis (EDA) techniques in Python. The primary objective is to analyze if death rates have reduced over time due to medical advancements and identify regions and causes with the highest under-5 death rates globally.

📂 Dataset
The dataset is sourced from the World Health Organization (WHO) and can be found here:
🔗 WHO Under-5 Mortality Dataset

🛠️ Technologies & Libraries Used
Python (Pandas, NumPy, Matplotlib, Seaborn)
Data Cleaning & Preprocessing
Exploratory Data Analysis (EDA)
Data Visualization

📌 Steps in Analysis
1️⃣ Data Cleaning & Preprocessing
Created a copy of the dataset for modifications
Removed unwanted columns
Checked for missing values
Renamed columns to avoid syntax errors
Filtered useful columns for analysis

2️⃣ Exploratory Data Analysis (EDA)
A. Year-wise Trends
✅ Analyzed the correlation between years and under-5 mortality rates
✅ Identified how the death rates have changed over time
✅ Observed trends in top five countries with the highest deaths
✅ Determined which cause led to the highest mortality rates each year

B. Income Group Analysis
✅ Compared total death rates per income group
✅ Analyzed cause-based differences across income groups
✅ Explored region-based variations in income groups

C. Cause-wise Analysis
✅ Identified which cause had the highest mortality rates globally
✅ Observed trends in cause-based death rates over time

D. Regional Analysis
✅ Correlated entry counts to death rates across regions
✅ Examined regional trends in under-5 mortality over the years
✅ Identified regions with the highest death rates annually
✅ Explored the distribution of income groups across different regions

📊 Key Findings & Insights
🔹 Year-wise Insights
📌 Under-5 mortality rates dropped significantly from 12.28M in 2000 to 7.03M in 2021, likely due to medical advancements, vaccination coverage, and improved healthcare.
📌 China and India showed a continuous decline in death rates, whereas Nigeria saw a rise after 2010.
📌 Prematurity was the leading cause of death every year.

🔹 Income Group Analysis
📌 Lower-middle-income countries had the highest death rates, while high-income countries had the lowest.
📌 Prematurity, birth asphyxia, and birth trauma were the top causes of deaths in lower-income groups.
📌 Europe had the most high-income groups, while Africa had the most lower-middle-income groups.

🔹 Cause-wise Insights
📌 Prematurity had the highest global mortality rates, followed by birth asphyxia and respiratory infections.

🔹 Regional Insights
📌 South-East Asia had the highest mortality rates until 2010, but after that, Africa surpassed it.
📌 Europe had the lowest death rates despite having the highest number of data entries.
📌 Regions like Americas and Europe had no low-income groups, indicating stronger economies and healthcare systems.


📁 Repository Structure
📂 EDA-WHO-Dataset
│── 📜 WHO_Under5_Mortality.csv       # Raw Dataset
│── 📜 EDA_WHO.ipynb                  # Jupyter Notebook with analysis
│── 📊 Visualizations/                 # Folder with generated plots
│── 📜 README.md                       # Project Documentation






