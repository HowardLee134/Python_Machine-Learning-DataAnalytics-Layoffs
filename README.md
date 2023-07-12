# Python_Machine-Learning-DataAnalytics-Layoffs
This is a Comp 293 class project that analyzing a dataset with information about layoff dataset.  

## Project Description:
The "Analysis of Tech Layoffs and Economic Turmoil" project focuses on analyzing a dataset that provides insights into recent layoffs in the tech industry, particularly during the economic slowdown caused by factors like slow consumer spending and the impact of the COVID-19 pandemic. The dataset includes information on various variables such as company names, locations, industries, total number of employees laid off, percentage of employees laid off, funding stages, countries, and funds raised.

The project aims to address several research questions related to the tech industry and layoffs, such as the distribution of industries within the Bay Area, the relationship between industry and the percentage of layoffs, the impact of the pandemic on layoff numbers, the relationship between funds raised and total layoffs, and the distribution of industries across different countries.

To begin the analysis, the project starts by importing necessary libraries, reading the dataset using Pandas, and performing initial exploratory data analysis. The distribution of industries within the Bay Area is visualized using a seaborn displot, which reveals the finance industry as the most prominent, followed by healthcare.

The project also explores potential outliers using a seaborn pairplot and identifies "funds_raised" as a variable with outliers. Filtering out the outliers, a scatterplot is created to visualize the relationship between the percentage of layoffs and funds raised.

Statistical analysis is conducted in the project as well. A t-test is performed to test for a difference in the percentage of layoffs between companies with a total layoff of 100 and companies with a total layoff of 300. Additionally, a linear regression analysis is conducted to examine the relationship between the percentage of layoffs and funds raised.

In the final part of the project, a quantitative variable from the dataset is chosen, and an attempt is made to predict its value based on all other quantitative variables. Multiple linear regression is employed for this task, and the model's performance is evaluated using train-test split and R-squared scores. The coefficients of the regression model are also examined to determine the variables with the most significant impact on the predicted variable.

Overall, this project provides a comprehensive analysis of tech layoffs and economic turmoil, examining various aspects of the dataset and exploring relationships between different variables. The findings can offer valuable insights into the effects of economic downturns on the tech industry and potentially inform decision-making processes for companies and policymakers in navigating similar challenges in the future.

