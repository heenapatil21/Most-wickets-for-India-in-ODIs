# Most-wickets-for-India-in-ODIs 🌐

The aim of this project was to leverage data analytics techniques to determine the best playing 11 for a given cricket tournament, specifically the ICC Cricket ODs. The project involved web scraping data from the ESPN Cricinfo website "https://stats.espncricinfo.com/ci/engine/records/bowling/most_wickets_career.html?class=2;id=6;type=team", transforming the data using Python and Pandas, and creating interactive EDA in python  for insightful visual representation.
The code retrieves the HTML content of the web page, parses it using BeautifulSoup, and then extracts data from the table on the page.

* Technologies Used:
  
Web Scraping: ESPN Cricinfo website

Programming Language: Python

Data Manipulation: Pandas

The code organizes the extracted data into separate lists for each statistic, and then creates a pandas DataFrame . Finally, the DataFrame is saved as a CSV file named "cricketinfo.csv" using the to_csv function, with the index parameter set to False to exclude the index column from the CSV file.

## Process : 
* Data Gathering: Scrapped data(tables) from the website.
* Data Cleaning: Cleaned the tables in perspective with missing values, column names, outliers.
* Exploratory Data Analysis: Created interactive offline visualizations using Ploty.
* Inferential Statistics: Drew conclusions from the data.

## Tools
* Python
* Beautiful Soup
* Matplotlib
* Pandas
* Seaborn
* Numpy
  
## EDA 

Exploratory data analysis helps you, as a data analyst, to look beyond the data. It is a never ending process — the more you explore the data, the more insights you get
