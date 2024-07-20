# Visualization-and-Solutions-for-Organizational-Improvement
The purpose of this service is to propose you with the new business idea and give some clear visualization 
to improve the current state of performance of the organization. Here in final project delivery, I came up 
with the complete visuals and theory of how the improvement of organization/company might take place 
using both the goal’s resultant visualization. Along with that I have also suggested few solutions based on 
the final result and observation of both the goals.
## SUB-GOAL:
 1. <b>Recognize the highest profitable types of jobs: </b> To survey the improvement of the organization on 
comparison of profitability of each job type.
2. <b> Optimize employee allocation:</b> To allocate the employes appropriately during peak or busy periods 
and diminish costs during slower or dead periods.

## DESCRIPTION OF EACH VISUALIZATION OF 1ST GOAL:
1. <b> Explanatory Visualization – ‘Invoice Amounts and Material Costs by Job Type’:</b>  In below bar 
graphs, each of the bar represents invoice amounts and material costs for each job type respectively. 
This bar chart shows the quick comparison of relative profitability of each job type using total 
invoice amounts and material costs. This is more likely to be helpful in recognizing which job type 
has higher invoice amounts or material costs. This chart shows that ‘water_feature’ job type has the 
highest invoice amount and material cost whereas ‘fall_planting’ has the lowest highest invoice 
amount and material. This information is further used to fulfill the requirement of our first goal, that 
is, to improve the profitability focusing on its revenue (how much is the cost of each job type and 
how much is spent on material) and find out the profit of each job type in one hour (highest and 
lowest profitable job type).

### Invoice Amounts and Material Costs by Job Type

![Invoice Amounts and Material Costs by Job Type](/Images_FinalProject/invoiceVSmaterialcost.png)

2. <b> Exploratory Visualization – ‘Profits by Job Type’: </b> To recognize and find the profitability of 
jobs, here I am finding the profits by job type as well as profits by job type per hour. The pie chart 
gives the high-level view of distribution of profits across job types by providing us the understating 
of proportion of total profit by each job type in percentage. Here user can use this chart to explore 
the data and make easy comparison between the job types to discover which job type generates the 
highest and lowest profits. The below pie chart shows that job type ‘water_feature’ has made the 
highest profit with 15.6%, whereas the lowest profitability is found for job type ‘fall_planting’ with 
1.4%, which depicts that the initial guess made by us from ‘Invoice Amounts and Material Costs by 
Job Type’ bar graph, is similar to the actual profit calculation.

### Profits by Job Type

![Profits by Job Type](/Images_FinalProject/PieChart.png)

3. <b> Interactive Visualization – ‘Correlation Matrix Heatmap’:</b>  Correlation Matrix Heatmap is very 
useful in understanding the correlation between different columns. Darker the color, stronger 
positive correlation, similarly lighter the color, weaker or negative correlation. This information can 
help you identify potential relationships and patterns in the data, which may be useful for further 
analysis and decision-making. Below heat map shows the stronger correlation between Profit and 
invoice amount, which indicates that if invoice amount increase, the profit also increases (the 
correlation value is also very close to 1). To make the below heat map interactive, I have given the 
hover functionality on every element of heat map to show the correlation between every column (X 
& Y axis), which will help us in understand which are positively correlated and which are negatively 
correlated. This I have achieved using ‘plotly.express’ for creating interactive visualizations with 
the Plotly graphing library.

### Correlation Matrix Heatmap

![Correlation Matrix Heatmap](/Images_FinalProject/Interactive%20Heatmap.png)

## DESCRIPTION OF EACH VISUALIZATION OF 2nd GOAL:
1. <b> Derived Data Type Visualization – ‘Average Profit Over Time’: </b> The below line plot will help 
us to analyze the allocation of employees accordingly in busy duration by assigning more resources 
and diminish during slower or dead period or reallocating the employees to other areas where it is 
busy. This is the major visualization to describe and implement our goal 2. This goal is depicted by 
the derived data by calculating the average profit over time, by calculating the total profit and then 
finding out is aggregate value. Below line graph shows the top 3 busiest months which is highlighted
as red dots on the line graph. This shows that in the month of April (4), May (5), June (6), it is 
required to increase the resources as compared to other months as these are the top 3 busiest months 
in the year.

### Average Profit Over Time

![Average Profit Over Time](/Images_FinalProject/Average%20Profit%20over%20time.png)
 
## OBSERVATION AND CONCLUSION OF GOAL 1: 

1. <b> Observation: </b> From the above 3 visualizations of goal 1 (Exploratory, Explanatory and Interactive) 
we can find out that, from ‘Invoice Amounts and Material Costs by Job Type’ graph, after
‘water_feature’ job type (which has the highest profit as per pie chart), ‘install_new_lawn’ and 
‘garden_landscaping’ has the highest invoice amount (both are almost equal), but on the other hand, 
difference in both the job type’s profit margin is highly noticeable. Job type ‘install_new_lawn’ has 
only 9.1% profit and ‘garden_landscaping’ (the second highest profitable job type in pie chart) has 
15.4% profit, even after almost same invoice amount. This can be noticed because, even though 
invoice amount is almost similar, there material cost has considerable difference. Job type 
‘garden_landscaping’ has low material cost which leads to high profit and job type 
‘install_new_lawn’ has high material cost which declines its profit value. From the above 
observation we can state that, higher invoice amount with lower material cost – eventually heads 
towards the more profit. Hence the organization can improve its profitability by focusing on every 
job type’s material cost by keeping it low so as to improve its revenue. 
Comparing, the two profits visualizations – pie chart for ‘Profits by Job Type’ and bar graph for 
‘Profits by Job Type per hour’, we can get additional insight into the profitability of each job type. 
Here we can clearly say that in ‘Profits by Job Type’ the highest overall/total profit was of 
‘water_feature’, whereas now it is the second highest in ‘Profits by Job Type per hour’ and 
'garden_landscaping’ had took its first position in profits per hour worked. This must be because 
‘water_feature’ job type requires lot of material cost or might have taken long time to complete the 
job. Hence to improve such kind of job types, the client must work on its material cost and the 
time/hours spend on the job.

<b> 2. Conclusion: </b> 
Below are the 5 job types which need the considerable improvement in their profits:
1. fall_planting has 1.4% profit
2. lawn_treatment has 3.6% profit
3. spring_cleaning has 4.7% profit
4. tree_pruning has 6.0% profit
5. retaining_wall has 7.4% profit
Below is the most profitable job type:
1. The most profitable job type is: water_feature
2. The least profitable job type is: fall_planting
3. The most profitable job type per hour is: garden_landscaping
4. The least profitable job type per hour is: fall_planting

## OBSERVATION AND CONCLUSION OF GOAL 2: 

1. <b>Observation:</b>  From the above derived data visualization of goal 2, we can clearly observe that the 
top 3 busiest months which are highlighted as red dots on the line graph, shows that in the month of 
April (4), May (5), June (6), there should be increase in the resource as they are the busiest months 
of the year whereas, we can see the huge decline in the average profit in the month of July (7) and 
October (10). Here in such declining profit’s months, we can reduce the work force.
2. <b> Conclusion:</b>  Analyzing the plot of goal 2, company can pre determine the allocation of resource 
according to busiest and the slower duration. This will help in optimizing the resource and reducing 
the unnecessary cost invested on resources who are siting ideal in slower duration.
