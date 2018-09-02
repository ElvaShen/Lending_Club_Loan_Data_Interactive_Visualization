# Lending Club Data Visualization Project

## Summary
The objective of this project is to understand trends of loan amount and gain insights through analyzing the Lending Club Loan Data from 2007 to 2015. The reason I chose this dataset was from my great interest in FinTech industry, and I believe learning what loan data looks like will help me better understand their business model and enhance my business acumen. In this project, I mainly used Python Plotly to generate interactive visualizations about the distribution of loan amount by state, by purpose and making comparison of loan amount and borrowers' income with respective loan grade. 

<img width="868" alt="screenshot 2018-09-01 00 43 08" src="https://user-images.githubusercontent.com/41976548/44943740-65caaa80-ad80-11e8-8038-ba8f237dec4f.png">

The first graph shows the Frequency Distribution of the Loan Amount.

<img width="865" alt="screenshot 2018-09-01 00 55 14" src="https://user-images.githubusercontent.com/41976548/44943837-cad2d000-ad81-11e8-8763-4dcaf4db6b97.png">




From these three graphs, we can tell the loans applied by potential borrowers, the amount issued to the borrowers and the amount funded by investors are similarly distributed, meaning that it is most likely that qualified borrowers are going to get the loan they had applied for.



Then I exhibited the [Total amount of Loan($) Issued by State From 2007 to 2015](https://plot.ly/~dandandesunshine/3).<br>(This is the interactive graph with the drop-down menu)

<img width="1417" alt="pic02" src="https://user-images.githubusercontent.com/41976548/44950371-dadac600-adfa-11e8-9827-cc943382a400.png">

It shows California, Texas, New York and Florida are the states in which the highest amount of loans were issued.<br>
There are some states that are blank, which does not necessarily mean that they are rich or do not borrow loans, it can simply be that Lending Club is not a popular lending company in those regions.



Then I explored the [Loan Issued by Purpose](https://plot.ly/~dandandesunshine/5).<br>

<img width="961" alt="pic03" src="https://user-images.githubusercontent.com/41976548/44950385-5dfc1c00-adfb-11e8-844e-23231dcf3417.png">



This shows debt consolidation is always the main reason for customers applying for loan.<br>
The top 3 purposes are debt consolidation, credit card, and home improvement.


Finally, I want to see the [Loan Amount vs Annual Income by Grade](https://plot.ly/~dandandesunshine/33) to get a sense of how Lending Club’s loan issuing strategy changes with time.

<img width="979" alt="pic04" src="https://user-images.githubusercontent.com/41976548/44950357-a5ce7380-adfa-11e8-819b-8f275a3a3062.png">


Lending Club’s loan issuing strategy is quite evident from this animation. At the beginning phase of their business, it was reasonable to take some risk by issuing loans to people with different annual income, while remain a low issuing amount to avoid too much loss.<br>
Over the time, after Lending Club discovers more patterns, and being more accurate in risk controlling, they increased the loan amount gradually, and put more emphasis on the customer group who have annual income within a smaller range.




## Interactive Graphs
[Total amount of Loan($) Issued by State From 2007 to 2015](https://plot.ly/~dandandesunshine/3)<br>
[Loan Issued by Purpose](https://plot.ly/~dandandesunshine/5)<br>
[Loan Amount vs Annual Income by Grade](https://plot.ly/~dandandesunshine/33)



## Source Code
The code is in Jupyter Notebook format named `Lending_Club_Loan_Data_Interactive_Visualization.ipynb`.
The Jupyter Notebook file is also available in [NBviewer](http://nbviewer.jupyter.org/github/elvashen/Lending_Club_Loan_Data_Interactive_Visualization/blob/master/Lending_Club_Loan_Data_Interactive_Visualization.ipynb)


## Datasets
The dataset is collected from Kaggle, it has cleaned data and thus easier to build visualizations.
https://www.kaggle.com/wendykan/lending-club-loan-data

This dataset has 75 variables in total, including numerical variables and many categorical variables with a range of unique cardinality from 3 to 30. In this project, I picked 10 variables to explore. They are:<br>
loan_amnt, funded_amnt, funded_amnt_inv, addr_state, issued_year(derived from original 'issue_d'), purpose, annual_inc, int_rate, grade, sub_grade.


