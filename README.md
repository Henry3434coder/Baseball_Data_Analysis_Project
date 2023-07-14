# Data Analysis Project: Exploring the Relationship between Payroll and Baseball Performance

## Overview
This is a data analysis project I completed during my sophomore year, where I had the opportunity to delve into statistical concepts and learn how to utilize the R programming language for data analysis. The project focused on analyzing a dataset containing baseball data from 1985 to 2016, specifically examining the relationship between team payrolls and various other variables.

## Objectives
The main objectives of this project were:
1. Understand the relationship between team payroll and baseball performance.
2. Utilize hypothesis tests to investigate the significance of relationships between payroll and other variables.
3. Develop predictive models to gain insights into the potential impact of payroll on team performance.

## Tools and Technologies
For this project, I utilized the following tools and technologies:
- R programming language
- RStudio (Integrated Development Environment)
- Excel (source data was provided in an Excel spreadsheet)

## Methodology
1. **Data Acquisition:** I obtained an Excel spreadsheet containing baseball data spanning from 1985 to 2016. This dataset provided the foundation for my analysis.

2. **Data Preparation:** I performed necessary data cleaning and preprocessing steps to ensure the data was in a suitable format for analysis. This involved handling missing values, standardizing variables, and merging relevant datasets.

3. **Exploratory Data Analysis:** I conducted exploratory data analysis to gain initial insights into the dataset. This included summarizing key statistics, visualizing distributions, and identifying potential relationships between variables.

4. **Hypothesis Testing:** I employed hypothesis tests, such as correlation analysis and regression analysis, to evaluate the significance of relationships between team payroll and other variables. This allowed me to determine whether payroll had a statistically significant impact on team performance indicators.

5. **Predictive Modeling:** I developed predictive models using regression techniques to predict team performance based on payroll and other relevant factors. These models helped me understand the potential influence of payroll on various performance metrics.

6. **Results and Interpretation:** I analyzed the findings from my exploratory analysis, hypothesis tests, and predictive models. I interpreted the results, drawing conclusions about the relationship between payroll and team performance, and providing insights into the factors that contribute to a team's success.

## Findings
### Hypothesis Testing
The analysis revealed that teams with higher payrolls tend to have a higher likelihood of winning their division. However, further statistical analysis is required to confirm the significance of this relationship.

### Predictive Modeling
The multiple linear regression model showed that payroll can be predicted to some extent using variables such as home runs, wins, ERA, win percentage, division ID, and hits. The model yielded an estimated regression equation:

payroll = 41.97 + 0.419 * HR + 0.5449 * W - 12.656439 * ERA - 81.84 * WinPercent + 0.0016 * H

However, it is important to note that the R-squared value of the model was relatively low (13.65%), indicating that the selected variables only explain a small portion of the variation in team payroll.

## Conclusion
In conclusion, this data analysis project examined the relationship between team payroll and performance metrics in Major League Baseball. The findings suggest that a higher team payroll may increase the likelihood of winning the division. Additionally, the analysis revealed that factors such as home runs, wins, ERA, win percentage, division ID, and hits can partially explain team payroll. However, it is evident that other factors not included in the analysis significantly influence a team's success. Therefore, a more comprehensive approach considering additional variables and factors is recommended for a deeper understanding of the determinants of team success in MLB.
