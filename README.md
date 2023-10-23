# Awesome-Chocolate-Dashboard
The project represents the Awesome Chocolate business dashboard where we are analysing month vise total amount spent by company,total cost(returns),total profit and profit %. All the above parameters are calculated by DAX query. Used different type of customized visualization like cards, Area chart, tables, slicers, filters etc.

# Tools Used:
Microsoft Excel, Power BI, Power Query, Power Pivot, Area chart, Tables, Slicers, Filters, Cards, DAX Query.

# Dashboard Analysis :
Total Amount, Total Cost, Total Profit, Profit % by per month from which business getting more profit also bottom 10 product from which bi=usiness not getting more profit so company can focus on them.Also we have added table to check sincerity od the sales person.Added one slicer to customized all data by team.

# Steps to be followed:
1)Load the data
2)Transform the data: clean the unclean data
3)See and manage relationsheep between tables
4)Create new measure by DAX function eg. Total Amount, Total Cost, Total Profit,Profit %
5)Create Dashboard

# Dax Function:
Total Amount=  SUM(sales[Amount])
Total Cost =   SUM(sales[Cost])
Total Profit = sales[Total Amount]-sales[Total Cost]
Profit % = DIVIDE([Total Profit],[Total Amount])
Profit target met = IF([Profit %]>0.5,"👍","👎")

# M function:
Cost = sales[Boxes]*RELATED(products[Cost per box])

![image](https://github.com/Arjunwadkarakshata/Awesome-Chocolate-dashboard/assets/138595946/5f2f1655-58d3-44c4-b006-210c119a97ac)
