

# Sales Insights-Dashboard

## Problem Statement

This dashboard helps the stakeholders understand their customers better. It helps the stakeholders know in which region sales are more and what products are being sold on higher quantity. Through different analysis, they get to know their improvement area, & thus they can improve their market strategies by identifying these area. For example even though Delhi is giving the highest Revenue but the profit margin is more in surat. It also lets them know the profit contribution % & revenue contribution %, thus since by using this dashboard they have identified issues, so they can further work on factors responsible for these unwanted loss.

Since, number of Sales Qty is declining in 2020 , they must work on improving their Market strategies based on the product quality, discounts, on product packaging etc to increase the sales. 

Also even though the profit target is 0% revenue contribution in Bengaluru is -ve. so stakeholders/sales manager should try to analyse based on the different factors.

### Project Goals
Here are the questions I would like the PowerBI dashboards to answer:

- Breakdown of sales for brick and motor vs e-commerce customers 
- Top 5 Customers with hieghest number of orders.
- Show the dynamic red alert in the dashboard whenever the performnace of the certain zone falls behind the certain profit target.
 - Revenue by Zone.
- Top 5 products by Revenue.
- Top 5 customers by Revenue.
- Sales Qty by Markets.
- Revenue by Markets.
- Sales Qty Trend.
- Revenue Trend.
- Revenue % and Profit % by Markets.

In order to answer these questions, I invested time in planning the PowerBI measures I would need to create and also planned a rough outline of the dashboard visuals I wanted.
### Data Analysis Summary
Here are the dashboards that I created. If you would like to actually play around with these dashboards see the end of this readme for instructions: 

![Key Insights](https://github.com/PAV9/Power-BI-projects/assets/50490983/18abebd9-fe27-4f68-9f0c-a87b2b345459)

![Profit Analysis](https://github.com/PAV9/Power-BI-projects/assets/50490983/4db5937e-9463-4e0b-a4d8-a3752f9530f3)

![Performance Insights](https://github.com/PAV9/Power-BI-projects/assets/50490983/c860738f-ab9a-465f-bf47-73ae0720e7d7)

### Hardware and Software Used

- MySQL
- Windows 11 Machine
- Microsoft PowerBI Desktop 

### Overview of Microsoft Power BI
Microsoft Power BI is a data analytics tool used to provide business intelligence capabilities, including loading, modelling, and visualizing data sets. Its initial release was over 10 years ago in July 2011, and since then the Microsoft team has continued to add greater functionality and improve ease-of-use on a monthly basis.

The program itself can be used both on a local machine (via Power BI "Desktop") and also on the cloud (via Power BI "Services"). It can be used in a similar fashion as how one may use Excel, but also provides the greater ability to more easily create interactive visualizations called 'dashboards'.


### Data Collection Methodology
I collected this sample data from github by codebasics. 

In order to import this data into PowerBI, first loaded the data into MySQl and then connect MySQL server to the Power BI.

### Data Cleaning
There was quite a bit of data cleaning to do. I had to do some basic steps in the power query editior like removing the columns which doesn't require for the calculations for this problem statement, changing the data types.

Finally, did some operations on filtering rows which shows sales amount < 0 and wrote M Query to convert the USD currency to the INR currency in sales transactions table. Removed the rows which shows the zone as null in sales markets table. 

### Measure and calculated column creation
In order to help answer the questions listed above, created few measures and calculated columns. some of the measures created are listed below.

- Total Profit Margin
- Total Revenue
- Total Sales Qty
- Revenue Last year
- Total Profit Margin %

And lastly i created a new parameter to show the dynamic red alert in the dashboard whenever the performnace of the certain zone falls behind the certain profit target.


## Conclusion
Using PowerBI stakeholders were able to visualize sales data in an interactive way. This allowed to drill deeper into sales behaviour in different zones and markets and with this information stakeholders can now make a new strategies to improve the business.

 


