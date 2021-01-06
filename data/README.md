## Data files for COMM318 _Stories from data_ Final Project



### Data files

##### RAW
* `linkedin_data_comm318.csv` 
This dataset is from Kaggle (https://www.kaggle.com/killbot/linkedin). Consists of 15000 anonymous profiles. Members for the most part are based in Australia. It contains 52 columns and data on their work history and analysis of their photo (Age, Race, Gender, Attractiveness, Health, Emotionality) and name.

* `linkedin_new.csv` 
Also from Kaggle (https://www.kaggle.com/killbot/linkedin-profiles-and-jobs-data), this data set consists of 10000 anonymous profiles, which are mostly based in Australia. It contains 27 columns and data on the company a user works at (company follower count, staff count) as well as data on the user (whether or not they have a profile picture, position duration, position title).

* `Fortune500.csv` 
This dataset is collected from Someka (https://www.someka.net/excel-template/fortune-500-excel-list/). It contains the names of companies on the Fortune 500 list, along with descriptors, such as the companies revenues and industries.

##### CLEAN
* `linkedin_original.csv`
This is the cleaned version of `linkedin_data_comm318.csv`. I've removed irrelevant columns, faulty rows, and renamed some other columns from the original dataframe.

* `linkedin_updated.csv`
This is the cleaned version of `linkedin_new.csv` . I've removed irrelevant columns, faulty rows, and renamed some other columns from the original dataframe.

* `Fortune500.csv`
I retained only the column with the company names from the original Fortune500 dataframe.