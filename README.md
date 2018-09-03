# Lending Club Data Visualization Project

## Summary
The objective of this project is to understand trends of loan amount and gain insights through analyzing the Lending Club Loan Data from 2007 to 2015. The reason I chose this dataset was from my great interest in FinTech industry, and I believe learning what loan data looks like will help me better understand their business model and enhance my business acumen. In this project, I mainly used Python Plotly to generate interactive visualizations about which states have the most loan issued, loan grades issuing trend and the relationship between the loan amount and borrowers' annual income with respect to loan grade. 

<img width="868" alt="screenshot 2018-09-01 00 43 08" src="https://user-images.githubusercontent.com/41976548/44943740-65caaa80-ad80-11e8-8038-ba8f237dec4f.png">

## Highlights

### 1. Loan Amount Frequency Distribution

<img width="1021" alt="pic01" src="https://user-images.githubusercontent.com/41976548/44997232-b2211080-af61-11e8-9f87-6db6ec12c8b6.png">




> We can tell that the loans applied by potential borrowers, the amount issued to the borrowers and the amount funded by investors are similarly distributed, meaning that it is most likely that qualified borrowers are going to get the loan they had applied for.



### 2. [Loan Issued by State](https://plot.ly/~dandandesunshine/3)<br>
(This is the interactive graph with the drop-down menu)

<img width="1417" alt="pic02" src="https://user-images.githubusercontent.com/41976548/44997253-d0870c00-af61-11e8-8840-32e37411f870.png">


> It shows California, Texas, New York and Florida are the states in which the highest amount of loans were issued.<br>
There are some states that are blank, which does not necessarily mean that they are rich or do not borrow loans, it can simply be that Lending Club is not a popular lending company in those regions.



### 3. [Loan Grade Issuing Trend(%)](https://plot.ly/~dandandesunshine/14)<br>

<img width="902" alt="pic03" src="https://user-images.githubusercontent.com/41976548/44997257-d67ced00-af61-11e8-977a-dead906700b1.png">




> It shows that the number of F and G grade loans issuance were very stable while others were volatile.


### 4. Animation: [Loan Amount vs Annual Income by Loan Grade](https://plot.ly/~dandandesunshine/38)
*try to get a sense of how Lending Club’s loan issuing strategy changes with time.*

<img width="979" alt="pic04" src="https://user-images.githubusercontent.com/41976548/44997263-d8df4700-af61-11e8-91c3-d365b279a850.png">


> Grade F and G loans were issued aggressively during 2011-2013, but 2012 was a year that the company made a pause and went back to a conservative plan.<br>
> Lending Club’s loan issuing strategy is quite evident from this animation. At the beginning phase of their business, it was reasonable to take some risk by issuing loans to people with different annual income, while remain a low issuing amount to avoid too much loss.<br>
> Over the time, after Lending Club discovers more patterns, and being more accurate in risk controlling, they increased the loan amount gradually, and put more emphasis on the customer group who have annual income within a smaller range.




## Interactive Graphs
[Total amount of Loan($) Issued by State From 2007 to 2015](https://plot.ly/~dandandesunshine/3)<br>
[Loan Grade Issuing Trend(%)](https://plot.ly/~dandandesunshine/14)<br>
[Loan Amount vs Annual Income by Loan Grade](https://plot.ly/~dandandesunshine/38)



## Source Code
The code is in Jupyter Notebook format named `Lending_Club_Loan_Data_Interactive_Visualization.ipynb`.<br>
In order to see the interactive graphs and play the animation, please check out the Jupyter Notebook file in [NBviewer](http://nbviewer.jupyter.org/github/elvashen/Lending_Club_Loan_Data_Visualization/blob/master/Lending_Club_Loan_Data_Visualization.ipynb).


## Datasets
The dataset is collected from Kaggle, it has cleaned data and thus easier to build visualizations.
https://www.kaggle.com/wendykan/lending-club-loan-data

This dataset has 75 variables in total, including numerical variables and many categorical variables with a range of unique cardinality from 3 to 30. In this project, I picked 10 variables to explore. They are:<br>
loan_amnt, funded_amnt, funded_amnt_inv, addr_state, issued_year(derived from original 'issue_d'), purpose, annual_inc, int_rate, grade, sub_grade.


