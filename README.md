# Dashboard Project: Adventure Works

## Brief description: 

This Power BI project tracks KPIs (sales, revenue, profit, etc.), compares regional performance, analyzes project- level trends, and identifies high- value customers.


# SQL Query

This query runs a QC report that shows all of the amount spent on financial assistance.


#Video Game Sales

##Recommended Analysis
1.	Which titles sold the most worldwide? 
•	Finding: Grand Theft Auto V was the most sold game of all time. 
•	Method: Utilized tables and cards to show the top game. In Sales by Region dashboard, you can see the Top 10 games.
2.	Which year had the highest sales? Has the industry grown over time? 
•	Finding: 2008 had the best year in sales. 
•	Method: Created a line chart as the visual and added a hierarchy for the years and months. You can drill drown on the linear graph to see the sales by year and month.
3.	Do any consoles seem to specialize in a particular genre? 
•	Finding: PC specializes more on adventure or strategy genres compared to the rest of the genres.
•	Method: By using Treemap as the visual, we can see that the consoles specialize in a particular genre.
4.	What titles are popular in one region but flop in another? 
•	Finding: There are titles that are more popular in one region than another. 
•	Method: By using table as the visual on the Total Sales Dashboard, we can see the games that were popular in one region and not popular in other regions. I created calculated columns using DAX (nested if statements) to show the popularity of the games by regions and then added these columns to the table.

Additional analysis:
•	Created an additional table in Power Query from the main raw table and unpivoted the regions sales to create the Sales by Region dashboard. Added steps to clean and move the necessary data for this dashboard.
•	Added an additional dimension table to connect the two fact tables (Pivoted and main raw file).
•	Created measures to calculate the counts of titles produced and then analyze in a cluster bar chart by publisher.


