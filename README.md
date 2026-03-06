# Experiment-11-Categorical-data-analysis-using-python

# Name: Shreyanshu Behera

# PRN : 25070123149

# Class: ENTC A1

# Aim

To study and perform categorical data analysis using Python and the Pandas library, utilizing techniques such as frequency counting, cross-tabulation, percentage distribution, filtering, and grouping on structured datasets.

# Theory

Categorical data represents types of data which may be divided into distinct groups or labels (e.g., categories like "Electronics", "Male", "Grade A"). Analyzing this type of data requires specific statistical techniques and functions to understand distributions and relationships:

Frequency Counts (value_counts()): Determines how many occurrences of each categorical label exist in a dataset.

Unique Values (unique(), nunique()): Identifies the distinct categories present within a feature and the total count of those unique categories.

Cross-Tabulation (pd.crosstab()): Creates contingency tables to understand the relationship between two or more categorical variables, useful for bivariate analysis.

Proportions and Percentages (normalize=True): Expresses the frequency of categories as a percentage of the whole, offering relative distribution insights rather than absolute numbers.

Filtering: Extracts specific subsets of data based on categorical conditions (e.g., isolating only the orders from the "Electronics" category).

Grouping (groupby()): Splits the data into distinct groups based on categorical criteria to perform multi-level aggregate calculations.

# Detailed Conclusion

The experiment successfully implemented categorical data analysis on two distinct datasets—a synthetic e-commerce dataset and a student performance dataset—demonstrating how Pandas can extract immediate, actionable insights:

E-commerce Data Insights:

Frequency distributions revealed that 'Electronics' is the most popular category.

Cross-tabulation highlighted strict purchasing patterns: 'Electronics' purchases exclusively used 'UPI', 'Clothing' used 'Cards', and 'Grocery' used 'Cash'.

The delivery methods ('Express' vs. 'Standard') were perfectly split at 50% each.

Student Data Insights:

The analysis of the 60 students showed a perfectly equal gender split (30 Male, 30 Female).

'Grade B' was the most common overall (40%), followed closely by 'Grade A' (36.6%).

Cross-tabulations revealed specific demographic performance gaps; for example, female students secured significantly more 'A' grades (14) compared to male students (8).

The CSE department had the highest enrollment (20 students), and grouping operations successfully detailed the specific grade distribution isolated within each of the four departments.

Ultimately, the experiment establishes that the Pandas library provides a highly efficient and comprehensive toolkit for summarizing, manipulating, and extracting meaningful patterns from categorical variables.
