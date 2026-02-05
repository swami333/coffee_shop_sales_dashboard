# COPY SHOP SALES DASHBOARD

<img width="1816" height="746" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/7e5cb362-af5b-4ab5-bc6f-24264f3fb8ab" />


## 1.Data Collection & Understanding
•	Imported raw coffee shop sales data into Excel
•	Reviewed columns such as:
	1.Transaction ID
	2.Date
	3.Product Category
	4.City
	5.Quantity
	6.Revenue
	7.Profit
•	Ensured correct data types (dates, numbers, text)

## 2.Data Cleaning & Preparation
•	Removed duplicate and blank records
•	Standardized category and city names
•	Created additional helper columns:
1.Year (from Date)
2.Month (from Date)
3.Weekday (using TEXT(Date,"ddd"))
•	Checked for missing or inconsistent values

## 3.Creating Calculated Fields (KPIs)
Used Excel formulas to calculate key metrics:
•	Total Transactions → COUNT(Transaction ID)
•	Total Quantity Sold → SUM(Quantity)
•	Total Revenue → SUM(Revenue)
•	Total Profit → SUM(Profit)
•	Revenue % by Year → Revenue ÷ Total Revenue

## 4.Building Pivot Tables
Created multiple pivot tables for analysis:
•	Category-wise transaction count
•	Weekday-wise transaction count
•	Monthly transaction trends
•	City-wise revenue distribution
•	Year-wise revenue comparison
Each pivot table was built with:
•	Proper sorting
•	Clear labels
•	Optimized layout for charts

## 5.Creating Pivot Charts
Converted pivot tables into interactive visuals:
•	Bar charts → Category & Monthly Transactions
•	Line chart → Weekday Transaction Trend
•	Donut chart → Yearly Revenue %
•	Pie chart → Revenue % by City
•	Stacked column chart → Monthly Revenue comparison

## 6.Adding Interactivity with Slicers
Inserted slicers for:
•	Year
•	Month
•	City
Connected slicers to all pivot tables to ensure:
•	Cross-filtering
•	Real-time updates across the dashboard

## 7.Designing KPI Cards
•	Created KPI cards using:
1.	Shapes
2.	Icons
3.	Linked cell values
•	Displayed:
1.	Total Transactions
2.	Total Quantity
3.	Total Revenue
4.	Total Profit
Focused on:
•	Clear visibility
•	Consistent formatting
•	Executive-style layout

## 8.Dashboard Layout & Formatting
•	Used a coffee-themed color palette
•	Applied consistent fonts and spacing
•	Rounded cards and aligned visuals
•	Removed gridlines for a clean UI
•	Ensured dashboard fits single screen view

## 9.Final Testing & Optimization
•	Tested slicers for accuracy
•	Verified KPI totals across all filters
•	Reduced unnecessary pivot cache usage
•	Optimized performance for smoother interaction

## 10.Final Outcome
An interactive Excel dashboard that:
•	Provides end-to-end sales insights
•	Supports quick decision-making
•	Demonstrates strong Excel, analytics, and visualization skills


