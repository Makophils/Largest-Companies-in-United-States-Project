## Largest-Companies-in-United-States-Project
In this Project, the dataset contains a list of the largest companies currently in United States by revenue as of 2023, according to the Fortune 500 tally of companies and Forbes. The goal of this project is to analyze the biggest companies in United States, companies with the highest revenue growth, Industries with the highest revenues and to establish if there was a correlation between size of workforce and revenue.
## Gathering (Scrapping) the data
The data was scrapped from Wikipedia on 2nd November, 2023 by 5PM GMT +1.The python request library was used to get the data from the Wikipedia URL, and the content of the URL was parsed via Beautiful Soup. The content was further wrangled to get a suitable pandas data frame that was used for the final analysis. The dataset was saved as CSV file.
## Summary of Findings  
The following insights were uncovered after the analysis:

•	The Top 5 Companies with the biggest revenue as at the time this analysis was done were Walmart, Amazon, Exxon Mobil, Apple and UnitedHealth group

•	The Top 5 Companies with the highest revenue growth TD synnex, World Fuel services, United Airlines, PBF Energy and ConocoPhillips 


•	The Top 5 Companies with the highest number of employees include Walmart, Amazon, United States Postal Services, FedEX and The Home depot.

•	Industries with the biggest revenue include retail, petroleum , Healthcare, financials and pharmaceuticals.


•	There was an inverse correlation between size of workforce and revenue growth. Companies with smaller number of employees had higher revenue growth  

