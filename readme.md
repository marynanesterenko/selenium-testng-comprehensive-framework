This is a Data-Driven Framework:

Data is stored in the spreadsheet format, it is kept separately from the Test Scripts,
so that the same Test Script can be executed for different combinations of input test data.

Test input values are read from the data files and stored into the variables in the Test Scripts.

Multiple data sets for a single test, importing the test data from an Excel file, while fetching it
from rows one-by-one and executing the Test Script.

APPROACH:

1. Identify the Test Cases
2. Create the Test Script
3. Create an Excel/CSV with the input Test Data
4. Modify the script to loop over the input Test Data with parameterized input commands

BEST PRACTICES:

1. Using PROD data
2. Code the navigation of the test flow inside the test script
3. drive virtual APIs with meaningful data
4. Use data to drive Dynamic Assertions

ADVANTAGES:

1. The ability to run one test with multiple sets of data is beneficial 
for optimized Regression Test Suite execution time.

2. Changes in the Test Script do not impact the Test Data.