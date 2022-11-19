[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://forthebadge.com)

# About the Project
Finding our client’s potential investment amount for further investing in stocks according to risk taking profile from the BSE 500 data that was provided 

## Aim
- First, we had to connect google sheets with python using Gspread
- Then, we had to use Income/Expense report of an individual to calculate his amount after expenses and that amount would have been the investment amount
- After that we had to use the BSE 500 data to see the best stocks to recommend based on that individual risk taking capacity

## Tech Stack used:
- Python(Numpy & Pandas)
- Google Sheets
- Gspread API
- Microsoft Excel
- Microsoft Powerpoint

## Prerequisite

- In order to use Gspread, one should hold google developer account so you can be assigned an authorization to connect Python with Gsheets, for more info on this  
  see the [video](https://www.youtube.com/watch?v=bu5wXjz2KvU)
- Python IDE, for this project I have used jupyter notebook
- Then excel, powerpoint to collate the date and make a dashboard that can be finally be shown through PPT
- Finally some knowledge about stocks, BSE to be specific 

## Pandas 

 ### Task One:
  
- Fist we with the help of Gspread imported the sheet in the python
- Then we used Pandas to create dataframe for all the particular files
- After that we calculated amount to be invested by substracting all the expense values from the income and displayed that amount that can be invested back into the
  gsheets
  
 ### Task Two:
 
 - There was already a drop down menu in the sheets which had 4 values containing risk taking profile, (Low risk taking, moderate risk taking,Risk taking,
   High risk taking)
 - Based on the changing drop down value we had to calculate their respective investemnt prospect. In other words which comapnies can the individual invest
   in.
   
   
## Dashboard
 
 ![image](https://user-images.githubusercontent.com/117629056/202873389-89aeaf80-ca4b-47d1-86bf-d593a65990fa.png)

 
 
 
 ## References 
[Gspread Documentation](https://docs.gspread.org/en/latest/)

[indicators used to assess stocks](https://www.getsmarteraboutmoney.ca/invest/investment-products/stocks/6-indicators-used-to-assess-stocks/)

[KPI for stocks](https://www.wallstreetmojo.com/key-performance-indicators/)

[Financial ratio analysis](https://tradebrains.in/financial-ratio-analysis-must-know/)

[Useful code](https://stackoverflow.com/questions/73136200/extract-values-from-pandas-groupby-into-a-new-dataset-combining-single-values)

[Updating multiple values at once using gspread](https://stackoverflow.com/questions/16675258/python-gspread-how-can-i-update-multiple-cells-with-different-values-at-once)

