# NY-Open-Crypto-Data-Analysis
An analysis of 15 different Crypto currencies during the September 16, 2026 New York (NY) Market Open session.

This project was done in three different stages, using three different softwares: Python, Excel, and Tableau. 

## Python
Python was used to write a script to retrieve the data used from an API containing the Crypto market data. It was
automated to retrieve data every 60 seconds from 8:30AM to 11:00AM. These times were chosen in attempt to get data right
when the market is usually most volatile, being the opening of the NY session. The data was turned into a csv, then imported into Excel.

## Excel
Excel was used to clean the data. There were a few formatting errors with the numbers. An extra column with added indexes was removed.
Other columns that were not to be used were removed, and column headers were standardized. Numbers were standardized to show two decimal places where appropriate and contain commas. The original uncleaned data is located in the Excel workbook, as well as the cleaned data used for the data analysis.

## Tableau
Tableau was used to present the data in meaningful ways. Five charts were created to analyze the data. The first is a chart used to display and compare the percent change in value each currency experienced during the time period the data was collected. The next was a line chart to display the percent change in value each currency experienced over the course to the NY open session. There is also a ranking of the coin market cap of each coin. Lastly, two currencies are further explored see there price action over the course of the session.

You can view the full dashboard of charts on my Tableau Public Profile: [Here](https://public.tableau.com/views/NYOpenCryptoAnalysis/CryptoNYOpen?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Sources
