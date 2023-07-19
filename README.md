# Bike Sales Excel Project

This is a personal Excel project to practice and demonstrate some important skills in Data Analytics, such as Data Cleaning, Pivot Tables and creating charts to build a Dashboard. The step-by-step approach can be found down below where I detail what I did to achieve the final result.

## Download and Installation

You can download the excel file in this repository to have access to the result of this project.

## Step-by-step approach

All the tasks were executed in the excel workbook file which initially only contained one sheet (the bike sales raw data):

1. Create a new sheet to store the data so we can modify it without changing the original raw data to preserve it, called 'Working_Sheet'.  
2. Create another separate sheet for pivot tables, called 'Pivot_Tables'.  
3. Create one more sheet to display all the visualization in a dashboard, called 'Dashboard'.  
4. Perform some data cleaning on the working data:  
&emsp;4.1 Enable filters in all the columns to look for spelling errors or inconsistencies in entries.  
&emsp;4.2 Delete duplicate rows.  
&emsp;4.3 Replace values in rows such as 'M', 'F' and 'S' with more appropriate values like 'Male'/'Female' and 'Married'/'Single' to make it easier to be understood.  
&emsp;4.4 Create new fields to group values which allows us to have interesting visualizations (Age_Group, Children_Group and Cars_Group).  
5. Study the data and decide what we could build with it:  
&emsp;5.1 Count of Purchased Bikes by Age Groups  
&emsp;5.2 If Purchased Bikes by Gender and Average Income  
&emsp;5.3 Count of Purchased Bikes by Commute Distance & Number of Cars  
&emsp;5.4 Count of Purchased Bikes by Marital Status & Children  
6. Select all the data to create the respective pivot tables.
7. Select each pivot table and create a chart off of it to be displayed in the 'Dashboard' sheet.
8. Format the dashboard for better visualization.
9. Insert slicers.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details.
