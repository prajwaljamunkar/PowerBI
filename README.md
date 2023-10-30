# PowerBI

Unit Testing in Power BI using Python



Test the DFG dashboard measures. Compare the SQL and dax and match them.


Step 1 : get the dax code of 2 measures of 1 visualization. You can write a simple dax code using dax code studio for the existing measure. Contact me for any questions.

Step 2: write equivalent SQL query to match the measure data from SQL server.

step 3 : create an Excel in which you will store measurename , SQL code , dax code which was in step 1 and step 2

Step 4 : write a python script which will read Excel file. Take the SQL code which is in Excel file. Connect to SQL server DB. Run the SQL code and get result.

Step 5: write a python code to fire the dax code and get the measure values from power bi service. use power bi API to do this.

Step 6 : compare step 4 and 5 result. If the results match then show pass. if results fail then show fail.

