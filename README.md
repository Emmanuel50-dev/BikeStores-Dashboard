# BikeStores-Dashboard
A complete data analytics project using SQL, Excel, and Tableau. The project involves generating  a dataset using SQL and use the dataset to create a Tableau dashboard, as well as an MS Excel dashboard.
The purpose of this project is to demonstrate my SQL,Excel, and Tableau abilities.

![Bikestores Dashboard 1](https://user-images.githubusercontent.com/76703169/220251306-2601e1b4-f7ab-467c-b3ac-d7d60df74960.png)
The dashboard is available [here](https://public.tableau.com/views/BikeStoresDashboard_16767919153100/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link) 

Below I outlined the steps involved in the creation of this dashboard.
## STEP 1. Installing the Database
First I installed the SQL Server Management Studio (SSMS) onto my local machine and ran the BikeStore database installation scripts locally. The scripts to create and load the database are available [here](https://github.com/Emmanuel50-dev/BikeStores-Dashboard/blob/main/SQL-Server-Sample-Database.zip)

If you're using SQL server, follow these steps to load the database:

1. Open SQL server, create a new database and give it a name (e.g. BikeStore)
2. Select the new database in the SQL server
3. Open the zip downloaded from the link I provided 
4. Open the 'create objects' query file and then execute it in the SQL server
5. Open the 'load data' query file and then execute it in the SQL server


## STEP 2. Writing the Scripts
I used the database schema to join the tables together and wrote SQL queries to select and transform the data for my tables: The SQL code to transform the data and create these tables is available [here](https://github.com/Emmanuel50-dev/BikeStores-Dashboard/blob/main/SQLQuery1.sql) 
Certain code snippets are also available at the bottom of this README file

## STEP 3. Connecting SQL dataset to Excel Workbook
Here's what happened in this phase
1. Creating PivotTables and PivotCharts
2. Stopping PivotTable Grouping from affecting another PivotTable
3. Creating a graph with multiple lines (series)
4. Creating map chart
5. Setting up Excel dashboard
6. Adding slicers to make Excel dashboard interactive

The final excel dashboard is available [here](https://github.com/Emmanuel50-dev/BikeStores-Dashboard/blob/main/Bike%20Stores.xlsx)

##  STEP 4. Creating the dashboards

The last step involved creating a Tableau dashboard. Tableau functionality and features used:

Dynamic Parameters
Parameter Actions
Level of Detail Expressions
Navigation Buttons
Custom Shapes and Custom Number Formatting

Here's the step by step process involved in developing the dashboard
1. Connecting Excel dataset to Tableau Workbook
2. Making charts
3. Using parameters and sets to make Top N chart
4. Creating banner and action filters for dashboard
5. Creating the executive dashboard
6. Making executive dashboard interactive
7. Using calculated field to make text contextual
8. Saving dashboard to the Tableau Public server


## SQL Code Snippets
