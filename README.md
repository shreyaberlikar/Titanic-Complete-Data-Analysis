# Titanic Complete Data Analysis

## 📌 Overview
This project presents a **complete end-to-end analysis of the Titanic dataset** using Python. It covers **data exploration, cleaning, feature engineering, and visualization** using NumPy, Pandas, Matplotlib, and Seaborn. The analysis demonstrates handling missing values, computing statistics, creating new features like `FamilySize`, normalizing data, encoding categorical variables, and exploring patterns in passenger demographics, fares, and survival.

---

## 📂 Dataset
The dataset used in this project is the **Titanic dataset**, which contains information about passengers such as:
- PassengerId
- Name
- Age
- Sex
- Pclass
- SibSp, Parch
- Fare
- Cabin, Embarked
- Survived  

> Note: The dataset should be saved as `Titanic-Dataset.csv` in the repository.

---

## 🔹 Steps Performed

### 1. NumPy Analysis
- Calculated mean, median, and standard deviation for Age.
- Handled missing values and replaced them with mean/median.
- Generated random age samples and computed correlations.

### 2. Pandas Basics
- Viewed first and last rows, checked dataset shape and summary statistics.
- Counted survival rates.
- Calculated average age per passenger class.
- Identified top fares and corresponding passenger names.

### 3. Data Cleaning
- Checked and filled missing values for `Age` and `Embarked`.
- Dropped `Cabin` due to many missing values.
- Replaced zero or negative fares with mean fare.

### 4. Encoding & Feature Engineering
- Binary encoding of `Sex` and one-hot encoding of `Embarked`.
- Normalized `Fare` using Min-Max scaling.
- Created new column `FamilySize = SibSp + Parch + 1`.

### 5. Data Visualization
- **Matplotlib:** Histograms, bar charts, line charts, scatter plots.
- **Seaborn:** Count plots, box plots, violin plots, heatmaps.

---

## 📊 Key Insights
- Majority of passengers were in **Pclass 3**.
- **Survival rate** varied significantly by sex and passenger class.
- Older passengers generally paid higher fares.
- Features like `FamilySize` and `Fare` show interesting relationships with survival.

---

## 🛠 Tools & Libraries
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 🔗 Usage
1. Clone this repository:
```bash
git clone <your-repo-url>
