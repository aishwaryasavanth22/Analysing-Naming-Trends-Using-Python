![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blueviolet)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)

### 📊 Exploratory Data Analysis of Historical Baby Naming Trends Using Python

This project performs Exploratory Data Analysis (EDA) on historical baby name datasets to uncover naming trends, gender-based birth distributions, and popular names across years.

By combining multiple yearly datasets and analyzing birth counts, the project identifies patterns in name popularity and demonstrates how data analysis techniques can reveal cultural and societal naming trends over time.

This project highlights core Data Science workflow skills including data extraction, data preprocessing, exploratory analysis, and data visualization using Python.

[Notebook Link](https://github.com/aishwaryasavanth22/Analysing-Naming-Trends-Using-Python/blob/b9f439d626dfcd549ae938ee96a155b65780c8e3/Analyzing%20Naming%20Trends.ipynb)

#### 🎯 Project Objective :
The goal of this project is to analyze historical baby name data in order to:

- Understand naming trends across years
- Examine male and female birth distributions
- Identify the most popular baby names based on birth frequency
- Visualize insights using Python data visualization techniques

Through this analysis, the project demonstrates how raw datasets can be transformed into meaningful insights using data analysis and visualization tools.

🧩 Problem Statement :

Naming trends evolve over time due to cultural, social, and demographic influences. Understanding these trends requires analyzing large historical datasets containing birth records and baby names.

The objective of this project is to explore historical baby name datasets and identify patterns in name popularity, gender distribution, and birth counts. By aggregating multiple yearly datasets and performing exploratory data analysis, the project aims to highlight the most frequently used names and visualize naming patterns over time.


#### 📌 Project Overview :

This project performs Exploratory Data Analysis (EDA) on historical baby name datasets to identify trends in naming preferences and gender-based birth distributions across multiple years.

Using Python data analysis libraries, multiple yearly datasets were extracted from a compressed archive, merged into a single dataset, and analyzed to uncover patterns in baby name popularity.

The project demonstrates practical skills in:

- Data extraction
- Data cleaning
- Data aggregation
- Exploratory data analysis (EDA)
- Data visualization

📂 Dataset Description :

The dataset contains historical baby name records collected over multiple years. Each record represents the number of babies born with a specific name in a particular year.

The dataset consists of yearly baby name records containing
- Name - The baby names
- Gender - Male(M) or Female(F)
- Birth Count = Number of babies born with that name.
- Year -Year of birth record.

The dataset files Were stored in a compressed ZIP format, and the files were programmatically extracted during the data preprocessing stage.

#### 🛠 Tools & Technologies : 
The following tools and libraries were used in this project:

- Python : Core Programming Language
- NumPy : Numerical computations
- Pandas : Data Manipulation & Analysis
- Matplotlib : Data Visualization
- ZipFile : Extracting compressed datasets
- BytesIO : In-memory file processing

These tools enabled efficient data extraction, transformation, analysis, and visualization.

#### ⚙️ Data Processing Workflow :

The following data preprocessing steps were performed:

1. Extracted baby name dataset files from a compressed ZIP archive using ZipFile and BytesIO.
2. Loaded individual yearly files into Pandas DataFrames.
3. Combined all yearly datasets into a single consolidated DataFrame to enable easier analysis across multiple years.
4. Verified the dataset structure and ensured data consistency and correctness.
5. Prepared the dataset for Exploratory Data Analysis (EDA).

#### 🔍 Exploratory Data Analysis :

Several analytical steps were performed to understand patterns in the dataset:

- Combined multiple yearly datasets into a unified DataFrame
- Analyzed the number of male and female babies born in specific years
- Aggregated total birth counts by gender
- Sorted baby names by birth frequency to determine popularity
- Extracted the Top 100 most popular baby names
- Identified the Top 10 most popular names based on birth counts

This analysis helped uncover patterns in naming preferences and gender distribution.

#### 📊 Data Visualizations :

To better understand the patterns in the dataset, several visualizations were created:

1️⃣ Gender Distribution

![Male Vs Female Babies Birth Distribution](https://github.com/aishwaryasavanth22/Analysing-Naming-Trends-Using-Python/blob/7cf57b447d6c1fb40b5a46001c24307bafb2c88e/Visualizations/Male%20Vs%20Female%20Birth%20Counts.png)

2️⃣ Aggregated Birth Counts

![Aggregated Birth Counts](https://github.com/aishwaryasavanth22/Analysing-Naming-Trends-Using-Python/blob/7cf57b447d6c1fb40b5a46001c24307bafb2c88e/Visualizations/Aggregated%20Birth%20Counts.png)

3️⃣ Top 10 Popular Baby Names

![Top 10 Popular Baby Names](https://github.com/aishwaryasavanth22/Analysing-Naming-Trends-Using-Python/blob/a350a185cba01d30237a62c6b29948369a17c0ec/Visualizations/Top%2010%20Baby%20Names.png)

These visualizations help clearly communicate naming trends and distribution patterns.

📈 Key Insights

The analysis revealed several interesting insights:

✅ Male and female birth distributions show consistent patterns across years.

✅ Certain names repeatedly appear among the most popular baby names.

✅ In the year 2010, popular baby names included:

- James
- Michael
- John
- Robert
- David
- Linda
- Mary

✅ These trends suggest that cultural influences and historical preferences significantly impact naming patterns.

💡 Skills Demonstrated :
This project demonstrates the following Data Science and Data Analysis skills:

- Data Cleaning
- Data Aggregation
- Exploratory Data Analysis (EDA)
- Data Visualization
- Trend Analysis
- Python Programming

🧠 Conclusion

This project demonstrates how Python-based data analysis techniques can be applied to explore historical datasets and uncover meaningful patterns. By combining multiple data files, performing exploratory analysis, and visualizing results, the project highlights how data can reveal long-term trends in naming preferences and gender-based birth distributions.

The analysis also demonstrates how EDA can provide valuable insights into cultural and societal trends reflected in naming practices.

🚀 Future Improvements

Potential enhancements for this project include:

- Analyzing baby name popularity trends across decades
- Creating interactive dashboards using Power BI or Tableau
- Performing time-series forecasting to predict future baby name trends
- Applying machine learning models to forecast name popularity

👩‍💻 Author

Aishwarya Savanth
Aspiring Data Scientist | Machine Learning Enthusiast
Passionate about data analysis, machine learning, and AI-driven insights.

⭐ If you found this project helpful, consider starring the repository!






