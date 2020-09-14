# GoogleMeet Attendance
This program reads the name of the participants and marks the attendance of people present in the meeting directly in the excel sheet with python. The program is made using web scraping and automation using selenium and pyexcel.

## Prerequisites
Follow the following instructions to run the code in your local machine.

### Chromedriver
Install the web driver using [Google ChromeDriver](https://chromedriver.chromium.org/) link. Unzip the file, copy the path of the folder and paste it in line 32 of the code.

### Selenium
Install this package by typing the following code in terminal :
~~~
pip install selenium
~~~

## Openpyxl
Install this package by typing the following code in terminal :
~~~
pip install openpyxl
~~~

Create an excel workbook named `Google_Attendance`. Add a sheet named `Attendance Sheet`. Create the sheet in the following manner :
