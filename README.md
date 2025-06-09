# 🚢 Titanic Dataset Analysis with Data Visualization 

This project performs an in-depth analysis of the Titanic dataset using Python, pandas, seaborn, matplotlib, and scikit-learn. It includes data cleaning, exploratory data analysis (EDA), visualization,

---

## 📂 Dataset

The dataset used is the [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) from Kaggle, containing data about passengers aboard the Titanic, such as:

- Passenger class (Pclass)
- Name, Sex, Age
- Number of siblings/spouses and parents/children aboard
- Fare paid
- Survival status



## 📊 Exploratory Data Analysis (EDA)

### ✔️ Data Cleaning:
- Filled missing values in `Age` using the median.
- Identified missing values using a heatmap.
- Converted categorical variables (e.g., `Sex`) for model usage.

### ✔️ Descriptive Statistics:
- `.describe()`, `.info()`, and `.value_counts()` used for summary insights.
- Computed survival rate by class and average age by survival status.

### ✔️ Visualizations:
- `sns.pairplot()`: Showed relationships between features and survival.
- `sns.heatmap()`: Displayed missing data and correlation matrix.
- `sns.boxplot()`: Compared age distributions of survivors and non-survivors.
- `sns.histplot()`: Analyzed fare distribution.
- `sns.scatterplot()`: Visualized age vs fare, colored by survival.
