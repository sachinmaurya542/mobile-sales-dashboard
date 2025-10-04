Mobile Sales Dashboard
An interactive Power BI report analyzing mobile phone sales with dashboards for:
Dashboard (overall KPIs)


MTD Report (month-to-date metrics)


Same Period Last Year (YOY comparison)


📂 Data & Measures
Main table: Sales Data


Columns: Transaction ID, Date, Brand, Units Sold, Price Per Unit, Customer, City, Payment Method, Ratings, Mobile Model


Measures:


Total_Quantity = SUM(Units Sold)


Total_sales = SUMX(Units Sold * Price)


Transactions = COUNTROWS(Sales Data)


Average_Price = AVERAGE(Price)


MTD = TOTALMTD([Total_sales], Calendar[Date])


Same Period Last Year = CALCULATE([Total_sales], SAMEPERIODLASTYEAR(Calendar[Date]))


🚀 Usage
Open .pbix in Power BI Desktop.
Explore pages: Dashboard, MTD, YOY.
Apply filters by brand, date, region.


📸 Visuals
KPIs: Sales, Quantity, Transactions, Avg Price


Trends & comparisons (MTD, YOY)


Brand/Model breakdowns.

Contact For question or Feedback, feel  free to Reach out.
-Github: https://github.com/sachinmaurya542
-Email:2000sachinmaurya@gmail.com




