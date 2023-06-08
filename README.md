>In case the chrome driver is outdated:
Check chrome version top right of browser -> help -> google chrome driver:
==========================================================================
## 92.0.4515.107 (Official Build) (32-bit)
[Click for Chromedriver website](https://sites.google.com/chromium.org/driver/downloads)

Welcome to Tae's beautiful scraper
==================================

## Example of excel file output  
![preview](https://github.com/teatae/MTLjobscraper/blob/main/preview.png?raw=true)  
Filename is report-mtl.csv  

There are 4 cases of incoming data  
Data format is [Title, Salary, Company, Location, Date, Website, URL]  
we will refer to [Title, Salary, Company, Location] as mainData  

same URL same mainData, we do NOTHING, it's a duplicate !  
same URL different mainData, we UPDATE the mainData  
different URL different mainData, we ADD this  
different URL same mainData, we UPDATE the URL  

data_Website are tables containing the following :[Title, Salary, Company, Location, Date, Website, URL]  
data_Website_writer is used to format data_Website into a csv string  
if Backup file is bigger than file, Backup file 'report-mtl - Copy.csv' is not overwritten  

Column names are Title,Salary,Company,Location,Date,Website,URL  
Processes each line of report-mtl.csv  

##### Get Win32 zip

pip install --upgrade pip  
pip install selenium  
py -m pip install selenium webdriver-manager  
