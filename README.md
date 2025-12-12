# Titanic Data Analysis with Python

This project examines the Titanic passenger dataset using Python, pandas, and Matplotlib. The goal is to explore survival patterns and understand how demographic and socioeconomic factors influenced passenger outcomes. The analysis includes data cleaning, exploratory data analysis, visualizations, and a set of focused questions that help uncover meaningful insights from the dataset.

---

## Dataset

The dataset used in this project is `titanic.csv`, a structured table in which each row represents a single passenger aboard the RMS Titanic. Some of the key features include:

- Survived — Whether the passenger survived (0 = no, 1 = yes)
- Pclass — Passenger class (1st, 2nd, or 3rd)
- Sex — Male or female
- Age — Passenger age in years
- Fare — Ticket price paid
- SibSp — Number of siblings or spouses aboard
- Parch — Number of parents or children aboard
- Embarked — Port where the passenger boarded

This dataset is commonly used for learning and demonstrating data exploration and analysis techniques.

---

## Project Overview

The analysis proceeds through several stages:

### Data Cleaning and Preparation
- Handling missing values
- Adjusting data types
- Creating additional useful features such as `SurvivedLabel` and `FamilySize`

### Exploratory Data Analysis
- Examining the data structure and summary statistics
- Identifying patterns in the variables
- Exploring distributions of age, fare, and class

### Visualizations
The project uses Matplotlib to generate:
- Histograms for age and fare distributions
- Bar charts for survival rates by sex, class, and embarkation port
- Line charts to explore survival patterns based on family size
- Boxplots to compare fare distributions across survival outcomes

### Key Questions Explored
The notebook investigates several questions, including:
1. What is the overall survival rate among passengers?
2. How do survival rates differ between male and female passengers?
3. Is there a noticeable difference in survival across passenger classes?
4. How does age vary among survivors and non-survivors?
5. What is the relationship between ticket fare and survival?
6. Does family size have an impact on survival probability?
7. Are survival rates affected by the port of embarkation?

---

## Insights

The results highlight several strong patterns in the data:

- Female passengers had significantly higher survival rates than male passengers.
- First-class passengers survived at substantially higher rates than those in second or third class.
- Younger passengers, especially children, show higher survival tendencies.
- Passengers who paid higher fares were generally more likely to survive.
- Individuals or small family groups tended to have better outcomes compared to very large families.
- Survival rates differed by embarkation port, which likely reflects differences in socioeconomic background and ticket class distributions.

These findings help illustrate how demographic and structural factors played a major role in survival outcomes during the sinking of the Titanic.

---

