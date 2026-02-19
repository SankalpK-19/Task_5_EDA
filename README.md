# Task 5: Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset to extract meaningful insights using statistical methods and visualizations. The objective is to understand data patterns, relationships, trends, and anomalies before applying any predictive modeling.

---

## 🎯 Objective
- Explore and understand the dataset structure
- Identify missing values and data types
- Analyze distributions and relationships between variables
- Visualize trends using plots
- Summarize key insights from the data

---

## 📂 Dataset Used
Dataset Name: Titanic Dataset (`train.csv`)  
Source: Kaggle – Titanic: Machine Learning from Disaster

## Key Columns:
- `Survived` – Survival status (0 = No, 1 = Yes)
- `Pclass` – Passenger class
- `Sex` – Gender
- `Age` – Age of passenger
- `Fare` – Ticket fare
- `Embarked` – Port of embarkation

---

## Tools & Libraries Used
- **Python**
- **Google Colab**
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualizations

---

## EDA Steps Performed

 1️. Data Understanding
- Used `.head()`, `.shape`, `.info()`, `.describe()`
- Identified missing values using `.isnull().sum()`

 2️. Univariate Analysis
- Histogram for Age distribution
- Count plot for survival status

 3️. Bivariate Analysis
- Survival vs Gender
- Survival vs Passenger Class

 4️. Multivariate Analysis
- Pairplot to analyze relationships among multiple variables

 5️. Correlation Analysis
- Heatmap to identify correlation between numerical features

 6️. Outlier Detection
- Boxplot analysis for Fare column

---

## Visualizations Used
- Histograms
- Count plots
- Box plots
- Pair plots
- Heatmap

---

## Key Insights
- Female passengers had a higher survival rate than males
- Passengers in 1st class had better survival chances
- Fare shows a positive correlation with survival
- Age and Cabin columns contain missing values
- Fare distribution is right-skewed with visible outliers

---
## Outcome
This project helped in developing skills related to:
- Data exploration and understanding
- Statistical analysis
- Data visualization
- Drawing meaningful business and analytical insights from raw data

---

## Author
**Sankalp Kavalekar**
