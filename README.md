# Titanic-Exploratory-Data-Analysis
Exploratory Data Analysis on the Titanic dataset using Python

# 🚢 Titanic Exploratory Data Analysis (EDA)

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the factors that influenced passenger survival.

The workflow includes:

* Data loading and inspection
* Data cleaning and preprocessing
* Data visualization
* Extracting meaningful insights

---

## 📂 Dataset

The dataset contains passenger information such as:

* Survival status (`Survived`)
* Passenger class (`Pclass`)
* Gender (`Sex`)
* Age (`Age`)
* Fare (`Fare`)
* Embarkation port (`Embarked`)

---

## 🧹 Data Cleaning

The dataset contained missing values, which were handled as follows:

* Filled missing **Age** values using the median
* Filled missing **Embarked** values using the mode
* Dropped the **Cabin** column due to excessive missing values
* Removed unnecessary columns like `Name`, `Ticket`, and `PassengerId`

---

## 📊 Data Visualization

The following visualizations were created:

* Survival count
* Survival by gender
* Survival by passenger class
* Age distribution
* Correlation heatmap
* Age vs Survival (boxplot)

---

## 🔍 Key Insights

* Females had a higher survival rate than males
* Passengers in **1st class** had better survival chances
* Higher fare passengers were more likely to survive
* Younger passengers had slightly higher survival rates

---

## 🛠️ Tools & Libraries

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 🚀 How to Run

1. Clone the repository
2. Open the Jupyter Notebook
3. Run all cells

---

## 📎 Project Structure

* `Titanic_EDA.ipynb` → Main notebook
* `Titanic-Dataset.csv` → Dataset

---

## 📌 Conclusion

This project demonstrates how **EDA techniques** can be used to clean data, visualize patterns, and extract meaningful insights from a dataset.

---

## 👤 Author

**Khan Ibrahim Irshad**
