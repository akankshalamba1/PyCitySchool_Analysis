# PyBer_Analysis
Analysis of District School

## Summary of Findings: 

In this assignment we work on District school data, we work on a CSV file with 19515 columns and 8 rows. Our goal for this challenge is to evaluate the data using Pandas and to draw the conclusion based on it. The software we used for this analysis is Jupyter notebook to write our code. 
Through out our evaluation we performed following steps to model the data:

1. Collect the student data into a DataFrame.
2. Prepare a cleaned version of the DataFrame.
3. Summarize key pieces of the data.
4. Drill down into the data to analyze specific subsets.
5. Compare and contrast the data through grouping and aggregation functions.

During our analysis we used functions like: .dtype, .isna(), .sum(), .dropna(), .duplication(), .replace, .mean(), .min() and .groupby() function. 


## Analysis outcome: 

Out of 15 schools Montgomery High school has the most number of student(2038) and Chang High school has the least number of students(171). Charter school has 872625.656236 school_budget and Public school has 911195.558251 school_budget. Average grade of grade 9, 10, 11, 12 for Charter school is 70.077874, 66.443206, 68.024735, 60.212121, if we compare the Charter school with Public school, Charter school has higher average marks. Whereas Public school grade 12 has more average marks(63.568319). 


## Additional analysis: 

- Charter and Public school grade avaerage for reading_score: It will help us compare both the school type based on there reading score. If the average reading_score of Charter school is high for all the grades similar to the math_score. We could futher look into factors that are contributing to low score of Public school and evaluate the corrective actions.

- Using loc function to find reading and math score of different grade: As we use the loc function to find the reading score for grade 10 for Dexon High school we could also drill down the analysis of different grades. 
