# Automated Spreadsheet Testing & Validation
A python based project for automated testing and validation spreadsheets used in a regulated environment, e.g. pharmacy and medical technology.

##Background
Spreadsheets are often the preformed form for data entry in many companies, including those acting in a regulated environment. In these instances spreadsheets are considered non-product software and have to meet similar regulatory standards as stand-alone software. It is therefor essential to thoroughly test and validate spreadsheets to a software standard, but which can be a lengthy, tedious and very repetitive procedure and frankly a waste of time and resources. 

##Solution
This project aims to provide a software with user interface that can be used to run simple tests on spreadsheets. The scope so far is:
*Opening spreadsheet
*Saving spreadsheet
*Entering data into specified cells and ranges
*Checking cell font color and background color as visible to the user (i.e. checking conditional formatting)
*Checking descriptive statistics calculations over specified ranges (Mean, SD, CV, Median, Min, Max)
*Checking cell protection

##Implemenation
The project will be implemented in Python. The project interface will be styled using PyQt5, while the backend will be based on pandas and xlwings modules.

