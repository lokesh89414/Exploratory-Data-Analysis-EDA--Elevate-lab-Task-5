# Exploratory-Data-Analysis-EDA--Elevate-lab-Task-5
# Titanic Survival Prediction - Exploratory Data Analysis (EDA)

## Overview
![Titanic](https://upload.wikimedia.org/wikipedia/commons/thumb/f/fd/RMS_Titanic_3.jpg/800px-RMS_Titanic_3.jpg)
This project performs an exploratory data analysis (EDA) on the Titanic dataset to uncover patterns and factors that influenced survival. The analysis uses Python with Pandas, Matplotlib, and Seaborn to visualize relationships and trends in the data.

## Dataset
The Titanic dataset contains information about 891 passengers with the following key features:
- **Survived**: Target variable (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Sex**: Gender of passenger
- **Age**: Age in years
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Fare**: Passenger fare
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Key Findings

### 1. Survival Rate by Gender
![Survival by Gender](https://i.imgur.com/4QzRZ9m.png)
- Females had significantly higher survival rate (74%) compared to males (19%)
- "Women and children first" protocol was clearly followed

### 2. Passenger Class Impact
![Survival by Class](https://i.imgur.com/8KXoY9g.png)
- 1st class passengers had 63% survival rate
- 3rd class passengers had only 24% survival rate
- Higher classes had priority access to lifeboats

### 3. Age Distribution Analysis
![Age Distribution](https://i.imgur.com/V5LdGQf.png)
- Children (<10 years) had highest survival rate
- Most passengers were between 20-40 years old
- Elderly passengers (>60) had lower survival rates

### 4. Fare Correlation with Survival
![Fare Distribution](https://i.imgur.com/7jXqZ7r.png)
- Higher fare passengers had better survival chances
- Clear negative correlation between Pclass and Fare
- Most fares were under $50 (right-skewed distribution)

### 5. Embarkation Port Patterns
![Embarkation Analysis](https://i.imgur.com/5bJtK1f.png)
- Cherbourg passengers had highest survival rate (55%)
- Most passengers embarked at Southampton
- Queenstown passengers had lowest survival rate

### 6. Family Size Impact
![Family Size](https://i.imgur.com/1fZcJ8r.png)
- Passengers with 1-3 family members had better survival odds
- Solo travelers and large families (>4) had lower survival rates

### 7. Feature Correlations
![Correlation Heatmap](https://i.imgur.com/2kGQjqy.png)
- Fare shows strongest positive correlation with survival
- Pclass shows strongest negative correlation with survival
- Age shows moderate negative correlation with survival

###Conclusion
The EDA revealed that gender, passenger class, and fare were the strongest predictors of survival. Women, children, and higher-class passengers had significantly better survival rates. These insights can inform feature engineering for predictive modeling.
