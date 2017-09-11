# Responses to a Business Analyst Test

Responses to a Business Analyst [test](http://competitiveanalytics.com/employment/business-intelligence-analysts/) based on the Alteryx platform.

<strong>Exercise 1: Data Prep Qualtrics Survey Parsing<\strong>

- Objective: The data contained in the field: “DownloadData” needs to be parsed effectively for analysis. Please reshape the data from the Input (results from a download tool) and parse into a table for analytics.

- Tools to Investigate: Text to Columns, Sample, Dynamic Rename


<strong>Exercise 2: Spatial Trade Area Creation<\strong>

The Customer File contains Total Sales and Total Visit Data to a Store.
The Customers visit the stores in the Store File.

- Objective: Create a Convex Hull Trade Area that encapsulates 80% of the customer base who spend more than $10 and have had more than 1 visit for each store. The 80% should define the closest customers to the store location.
Question: For the 3 stores, what is the Area Sq Miles for each Trade Area?

- Tools to Investigate: Join, Distance, Poly Build, Spatial Info


<strong>Exercise 3: Preparing Sales Data for Visualization<\strong>

A company would like to visualize their sales data in tableau. The source data contains monthly data for two months (Jan, Feb), two reporting types (customer count and revenue), and various classes of business (NB, NBEC, ECR, ECUR, Total).

- Objective: This data needs to be transposed into a format that is easily visualized in Tableau.

- Tools to Investigate: Filter, Multi-Row Formula, Transpose


<strong>Exercise 4: Time Series Forecasting<\strong>

A retailer would like to forecast how many units of a particular product will be purchased from their locations based on a historical trend.
The source data contains weekly data for 2012 and 2013 details how many units have been moved. Some of the data, however, is populated with NULL values. For the NULL values, please assign the monthly average. If the monthly average is also NULL, assigned the annual average.

- Objective: Forecast how many units will be moved for the next 6 weeks.

- Tools to Investigate: Formula, ARIMA, Summarize
