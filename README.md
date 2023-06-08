Welcome to Tae's beautiful scraper
==================================

## Example of excel file output  
![preview](https://github.com/teatae/MTLjobscraper/blob/main/preview.png?raw=true)  
Filename is report-mtl.csv  

## Console output  
![preview](https://github.com/teatae/MTLjobscraper/blob/main/preview2.png?raw=true)  

data_Website are tables containing the following :[Title, Salary, Company, Location, Date, Website, URL]  
data_Website_writer is used to format data_Website into a csv string  
if Backup file is bigger than file, Backup file 'report-mtl - Copy.csv' is not overwritten  

Column names are Title,Salary,Company,Location,Date,Website,URL  
Processes each line of report-mtl.csv  

## Commands 
pip install --upgrade pip  
pip install selenium  
py -m pip install selenium webdriver-manager  

## In case the chrome driver is outdated
Check chrome version top right of browser -> help -> google chrome driver:
[Click for Chromedriver website](https://sites.google.com/chromium.org/driver/downloads)
