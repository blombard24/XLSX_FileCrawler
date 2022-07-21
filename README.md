# XLSX_FileCrawler

This is a python script to search all folders and subfolders in a parent folder to load xlsx files via openpyxl. The can have a specified prefix ("quote", "agreement" "estimate" etc.) with the use of wild cards for extra characters. The loaded files are then passed through a for loop to extract values from specified cells assigning the values to a dataframe.

Next steps include cleaning and analysis on the resultant dataframe. 
