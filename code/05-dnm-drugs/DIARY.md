I'm interested in what drug demand looks like on the dark web. Gwern.net publishes a comprehensive archive of dark net market scrapes; the downside is that it's 1.5 TB uncompressed, it's all in HTML files (hundreds per day), and the data ends in 2015. (It took my laptop a full day to download everything and to extract data for a single small marketplace.) I also found a couple of datasets from 2014-2015 and 2016, with scrapes from Agora, Hansa, and Valhalla, which were popular markets that are now defunct. In addition, I'm looking through an SQL database from Carnegie Mellon, which has anonymized data for some markets through 2017. I had hoped to scrape the largest current market, but the interface was terrible.

The Economist did exactly what I had hoped to visualize with Gwern's data. I'd like to try to mimic their format, or to come up with other ways to visualize similar data. I'll most likely stick with the datasets that I found, and/or the CMU SQL database, since Gwern's data is probably too hefty for a n00b like me to parse in the time allotted.

**Data set(s):** 
Agora data from 2014-2015
https://www.kaggle.com/philipjames11/dark-net-marketplace-drug-data-agora-20142015
Sarah Jamie Lewis's Dark Web Data Dumps (2016)
https://polecat.mascherari.press/onionscan/dark-web-data-dumps
CMU Database:
https://arima.cylab.cmu.edu/


8/8
-Decided to retool the project a bit and only use CMU's datasets. Their public datasets are more limited and anonymized, but I've requested access to their complete databases through IMPACT. Unfortunately it can take up to 2 weeks for IMPACT to approve my account, which will be after the due date of this project!

-In the meantime, I'd like to chart sales over the 3 largest markets by volume of total sales (Alphabay, Silk Road 2, and Evolution) after Silk Road

-Then I'd like to combine data from the 3 markets and ape the Economist's chart

--------

8/9

-Downloaded datasets and created dataframes; made a donut charts showing cumulative sales for different categories on Alphabay

-------
 8/14
-Re-ordered and updated my donut chart per feedback
-Created donut charts for Evolution and Silk Road 2
 -------
 


