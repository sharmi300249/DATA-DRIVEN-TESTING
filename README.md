
**Company:** CODTECH IT SOLUTIONS

**Name:** SHARMILA

**ID:** CT08JVW

**Domain:** AUTOMATION TESTING.

**Duration:** January 5th, 2025 to February 5th, 2025.

**Mentor:** Neela Santhosh

## Project Overview 

### Project: DATA-DRIVEN TESTING



### Objective
The primary goal of this project is to automate the process of testing login functionality using Excel sheets to manage test data. The project leverages Apache POI for reading data from Excel files and TestNG for organizing and running the tests. This approach makes it easy to manage and update test data without modifying the code.

### Key Activities
ExcelUtils Class: A utility class to read data from Excel files using Apache POI. It provides methods to get row count, column count, and cell data from the specified sheet.

LoginTest Class: A TestNG test class that utilizes the data provider mechanism to fetch login data from the Excel sheet and run login tests.

Data Provider Method: Reads the Excel file, retrieves the test data, and supplies it to the test method. This makes it easy to manage test cases by simply updating the Excel file.

Test Method: Executes the login test using the data fetched from the Excel sheet. The results of the test are printed in the console.

### Technologies Used
Java: The core programming language used for writing the automation scripts.

Apache POI: A Java library used for reading and writing Microsoft Office documents, specifically Excel files in this project.

TestNG: A testing framework inspired by JUnit and NUnit, used for running the tests and managing the test lifecycle.
