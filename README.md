# elevatelab-titenic-EDA
 Understand data using statistics and visualizations.
#  Titanic Dataset Exploratory Data Analysis (EDA)

##  Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Titanic Dataset** to uncover patterns, trends, and insights related to passenger survival. The analysis includes statistical summaries, data visualizations, and feature-level inferences.

---

## Objectives
The main goals of this analysis are:
1. Generate **summary statistics** (mean, median, standard deviation, etc.)  
2. Visualize **distributions** using histograms and boxplots  
3. Examine **relationships between features** using correlation matrices and pairplots  
4. Identify **patterns, trends, or anomalies** in the dataset  
5. Make **basic inferences** from the visualizations  

---

##  Dataset Information
**File:** `Titanic-Dataset.csv`

Typical columns include:
- `PassengerId` — Unique ID for each passenger  
- `Survived` — 0 = No, 1 = Yes  
- `Pclass` — Ticket class (1st, 2nd, 3rd)  
- `Name` — Passenger’s name  
- `Sex` — Gender  
- `Age` — Passenger age  
- `SibSp` — Number of siblings/spouses aboard  
- `Parch` — Number of parents/children aboard  
- `Ticket` — Ticket number  
- `Fare` — Ticket fare  
- `Cabin` — Cabin number  
- `Embarked` — Port of embarkation (C, Q, S)

>  Note: Some columns or names may vary depending on dataset version.

---

## ⚙️ Requirements

Install the required libraries before running the script:

```bash
pip install pandas matplotlib seaborn
