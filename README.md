# Lending Club Data Visualization Project

## Summary
The objective of this project is to understand trends of loan amount and gain insights through analyzing the Lending Club Loan Data from 2007 to 2015. The reason I chose this dataset was from my great interest in FinTech industry, and I believe learning what loan data looks like will help me better understand their business model and enhance my business acumen. In this project, I mainly used Python Plotly to generate interactive visualizations about the distribution of loan amount by state, by purpose and making comparison of loan amount and borrowers' income with respective loan grade. 

<img width="868" alt="screenshot 2018-09-01 00 43 08" src="https://user-images.githubusercontent.com/41976548/44943740-65caaa80-ad80-11e8-8038-ba8f237dec4f.png">

The first graph shows the Frequency Distribution of the Loan Amount.

<img width="865" alt="screenshot 2018-09-01 00 55 14" src="https://user-images.githubusercontent.com/41976548/44943837-cad2d000-ad81-11e8-8763-4dcaf4db6b97.png">




From these three graphs, we can tell the loans applied by potential borrowers, the amount issued to the borrowers and the amount funded by investors are similarly distributed, meaning that it is most likely that qualified borrowers are going to get the loan they had applied for.



Then I exhibited the Distribution of Loan Amount by State From 2007 to 2015. This is the interactive graph with the drop-down menu.

<img width="993" alt="screenshot 2018-09-01 01 00 25" src="https://user-images.githubusercontent.com/41976548/44943904-f904df80-ad82-11e8-9edd-4ef850f5ad8b.png">


This shows debt consolidation is always the main reason for customers applying for loan.<br>
Almost all kinds of loans increase with year over the time, except for wedding and education. Also, the loan amounts for these two purposes are also the lowest among all the purposes. This is understandable because it’s natural for category with less loan amount to be more unstable comparing with category with more loan amount.








## Source Code
The code is in Jupyter Notebook format named `Lending_Club_Loan_Data_Interactive_Visualization.ipynb`.


## Datasets
The dataset is collected from Kaggle, it has cleaned data and thus easier to build visualizations.
https://www.kaggle.com/wendykan/lending-club-loan-data

This dataset has 75 variables in total, including numerical variables and many categorical variables with a range of unique cardinality from 3 to 30. In this project, I picked 10 features to explore. loan_amnt, funded_amnt, funded_amnt_inv, addr_state, issued_year(derived from original 'issue_d'), purpose, annual_inc, int_rate, grade, sub_grade.


