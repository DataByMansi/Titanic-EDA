# Titanic-EDA

This project performs an Exploratory Data Analysis (EDA) on the Titanic dataset, focusing on understanding the factors that affected survival rates on the Titanic. The analysis is performed using Python libraries like pandas, numpy, matplotlib, and seaborn.

## Dataset

The dataset used in this project is the Titanic training data (`train.csv`). It includes information about passengers on the Titanic, such as their age, sex, passenger class, and whether they survived or not.

## Steps Involved

1. **Load and Understand the Data**: 
   - Loaded the `train.csv` file.
   - Displayed basic information and checked for missing values.

2. **Data Cleaning**:
   - Filled missing values in the "Age" column with the median.
   - Dropped the "Cabin" and "Ticket" columns as they had many missing values.
   - Converted categorical columns like "Sex" and "Embarked" to numerical values.

3. **Exploratory Data Analysis**:
   - Visualized the distribution of the "Age" and "Fare" columns.
   - Analyzed survival rates based on features like "Sex", "Pclass", "Age", and "Embarked".
   - A correlation matrix was plotted to see the relationships between numerical features.

4. **Key Visualizations**:
   - **Age Distribution**: Shows the distribution of passengers' ages.
   - **Survival Rate by Sex**: Displays how survival rates differed between male and female passengers.
   - **Survival Rate by Passenger Class**: Displays how survival rates differed between different passenger classes.
   - **Stacked Bar Plot of Survival by Embarked**: Shows the survival rate based on the port of embarkation.

## Findings

- **Survival Rate by Sex**: 
   - The survival rate for female passengers was higher than for male passengers. 
   - This suggests that women had a better chance of survival, possibly due to the "women and children first" policy.

- **Survival Rate by Passenger Class**: 
   - Passengers in first class had a significantly higher survival rate than those in second and third classes.
   - This suggests that social class played an important role in survival, possibly due to proximity to lifeboats and better access to resources.

- **Survival Rate by Age**: 
   - Younger passengers had a higher chance of survival compared to older passengers.
   - This could indicate that children and younger adults were given priority during evacuation.

- **Port of Embarkation and Survival**: 
   - Passengers who boarded in Cherbourg had a higher survival rate than those who boarded in Queenstown or Southampton.

- **Correlation Analysis**: 
   - "Age" and "Fare" showed weak correlations with survival, but the "Pclass" and "Sex" had stronger correlations.

## Conclusion

This project provides valuable insights into the factors that influenced survival rates on the Titanic. It highlights the importance of gender, class, and age in survival chances. Further analysis could involve building predictive models based on these features to classify passengers.

## Requirements

- pandas
- numpy
- matplotlib
- seaborn


