# data-processing-python-project
Important note!
If you would like to test the dataCleaning notebook with most recent scraped data - use the dataCleaner_24.08.ipynb file inside the '24.08. data' folder.
For the analysis, the data from May (jobOffers.csv) were used due to the limited sample size of the scraped data in August. 
The website noluffjobs.com has partially changed its page source codes, therefore the form of the scraped data looks slightly different now in August in comparison to May (e.g. compare jobOffers.csv and jobOffers-24.08.).
DataCleaner.ipynb file only works for May data (jobOffers.csv) and DataAnalysis.ipynb file only works for cleaned May data (cleaned_data.csv).


How to use the files?
We would recommend to first open the '24.08. data' folder and run the dataScraper.ipynb and dataCleaner_24.08.ipynb files to control, whether we are able to scrape and clean the most recent data. If successful, than we would recommend to run the dataCleaner.ipynb file which will clean the preprocessed May data and then run the dataAnalysis.ipynb file to check our analysis on cleaned May data.

Use this link to view plotly charts from the dataAnalysis jupyter notebook:
https://nbviewer.org/github/leduca1/data-processing-python-project/blob/final_output/dataAnalysis.ipynb


![Screenshot 2022-08-26 at 7 52 19](https://user-images.githubusercontent.com/100155849/186831668-f3324000-aec0-4151-b269-34a3903cce94.png)
