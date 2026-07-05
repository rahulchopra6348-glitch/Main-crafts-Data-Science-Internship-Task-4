# 📊 Data Science with Python Internship – Task 4

## 📌 Project Title

**Mini Visualization Dashboard on Titanic Dataset**

---

## 📖 Project Overview

This project is a part of my **Data Science with Python Internship** at **Maincrafts Technology**.

The objective of this project is to build a **Mini Visualization Dashboard** using the Titanic dataset. The project includes data cleaning, feature engineering, exploratory data analysis (EDA), and multiple visualizations created using **Matplotlib** and **Seaborn**.

The dashboard helps communicate important insights about passenger survival, age distribution, fare, passenger class, and other key characteristics through clear and informative visualizations.

---

# 🎯 Objectives

The main objectives of this project are:

- Load and explore the Titanic dataset.
- Clean the dataset by handling missing values.
- Perform simple feature engineering.
- Create multiple visualizations using Matplotlib and Seaborn.
- Analyze passenger survival patterns.
- Present insights through a dashboard with proper interpretations.

---

# 📂 Dataset Information

**Dataset Name:** Titanic Dataset

The dataset contains information about passengers travelling on the Titanic, including:

- Passenger ID
- Passenger Class
- Passenger Name
- Gender
- Age
- Number of Siblings/Spouses
- Number of Parents/Children
- Ticket Number
- Fare
- Cabin
- Embarkation Port
- Survival Status

---

# 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 📋 Project Workflow

## Step 1 – Import Libraries

Imported the required Python libraries for data manipulation and visualization.

Libraries used:

- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Step 2 – Load Dataset

Loaded the Titanic dataset using Pandas and displayed the initial records to understand its structure.

---

## Step 3 – Dataset Exploration

Performed an overview of the dataset by checking:

- Shape
- Columns
- Data Types
- Missing Values
- Statistical Summary

---

## Step 4 – Data Cleaning

The following preprocessing steps were performed:

- Filled missing Age values using the median.
- Filled missing Embarked values using the mode.
- Removed the Cabin column because it contained many missing values.
- Removed duplicate records.

---

## Step 5 – Feature Engineering

Created two new features:

### Family Size

Family Size = SibSp + Parch

This represents the number of family members travelling together.

### Age Group

Passengers were categorized into:

- Child
- Teen
- Young Adult
- Adult
- Senior

These new features helped perform better analysis and visualization.

---

# 📊 Dashboard Visualizations

The project includes multiple visualizations to understand the dataset more effectively.

## 📈 1. Age Distribution Histogram

Shows the distribution of passenger ages.

**Insight**

- Most passengers were between 20 and 40 years old.
- Very few passengers were elderly.

---

## 📊 2. Survival Rate by Gender

Compares survival rates between male and female passengers.

**Insight**

- Female passengers had a much higher survival rate.
- Male passengers had a comparatively lower survival rate.

---

## 📦 3. Fare Distribution by Passenger Class

A box plot comparing ticket fares across passenger classes.

**Insight**

- First-class passengers paid significantly higher fares.
- Third-class passengers paid the lowest fares.

---

## 📉 4. Age vs Fare Scatter Plot

Shows the relationship between passenger age and fare.

**Insight**

- No strong relationship exists between Age and Fare.
- Higher fares are mostly associated with first-class passengers.

---

## 🔥 5. Correlation Heatmap

Displays correlations among numerical variables.

**Insight**

- Fare has a positive relationship with survival.
- Passenger Class has a negative relationship with survival.

---

# 🔍 Key Findings

- Missing values were successfully handled.
- Cabin column was removed because of excessive missing values.
- Female passengers had better survival rates.
- Young adults formed the largest passenger group.
- First-class passengers generally paid higher fares.
- Passenger Class influenced survival probability.
- Fare showed a positive relationship with survival.
- Feature engineering improved the quality of analysis.

---

# 📚 Skills Learned

Through this project, I gained practical experience in:

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Dashboard Creation
- Statistical Analysis
- Python Programming
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

# 🎓 Learning Outcomes

This project strengthened my understanding of:

- Handling real-world datasets
- Creating meaningful visualizations
- Interpreting graphical insights
- Communicating data findings effectively
- Building professional Jupyter Notebook reports

---

# 📌 Conclusion

The Mini Visualization Dashboard successfully demonstrates how visual analytics can be used to understand the Titanic dataset.

After cleaning the data and creating new features, multiple charts were developed to analyze passenger demographics, fare distribution, survival trends, and relationships among different variables.

The dashboard presents information in a simple and effective manner, making it easier to interpret important patterns within the dataset. This project enhanced my practical knowledge of Python-based data analysis and visualization, which are essential skills for every Data Analyst and Data Scientist.

---

# 👨‍💻 Internship Details

**Internship:** Data Science with Python Internship

**Organization:** Maincrafts Technology

**Task:** Task 4 – Mini Visualization Dashboard

---

## ⭐ Thank You!

Thank you for visiting this repository.

If you found this project useful, feel free to ⭐ star the repository and explore my other internship projects.
