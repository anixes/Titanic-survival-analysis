# Titanic-survival-analysis
An exploratory data analysis of the Titanic dataset to identify key factors influencing passenger survival.
An exploratory data analysis of the Titanic dataset to identify the key factors that influenced passenger survival. This project involves data cleaning, feature engineering, and visualization to uncover insights from this historic event.

This analysis seeks to answer the following questions:

How did socio-economic status (i.e., passenger class and fare) impact survival rates?

- Did gender and age play a significant role, in line with the "women and children first" protocol?

- What was the effect of family size on a passenger's chances?

- Is there a correlation between the port of embarkation and survival?

Analysis Workflow
Data Cleaning: Handled missing values in the Age, Embarked, and Deck columns using median and mode imputation to prepare the dataset for analysis.

Feature Engineering: Created family_size and age_group features to enable a more nuanced analysis of passenger demographics.

Visualization: Used Matplotlib and Seaborn to generate plots (bar charts, violin plots, KDEs) to visualize relationships and correlations between different passenger attributes and their survival outcome.

Summary of Findings
Gender and Age were critical: The "women and children first" protocol was strongly evident. Females had a ~75% survival rate vs. <20% for males. Children also had a significantly higher survival rate than adults.

Socio-Economic Status was a primary predictor: First-class passengers had the highest survival rate. The fare paid also showed a clear positive correlation with survival.

Small Families Fared Best: Passengers in family groups of 2-4 had a higher survival rate than those traveling alone or in large families (5+).

Embarkation Port was a confounding variable: While Cherbourg passengers had a higher survival rate, this was primarily because a higher proportion of first-class passengers boarded from that port.

Tools Used-

- Python

- Pandas

- Matplotlib & Seaborn

- Jupyter Notebook
