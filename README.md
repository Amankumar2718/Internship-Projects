# Internship-Projects
In this project, I used Netflix_title.csv file for data cleaning and data prepration for analysis by using python programing Language.
Firstly, I import Pandas libraries and OS module.
After that I load the dataset by using open and read query.
Then the next step is to preview the dataset so that wse get some overview what we will gone to do.
Then after preview, Firstly I check the null values by using the {isnull()} operation of pandas library.
After finding out null values my next task is fill or remove that null values and duplicates for getting better insight from the dataset.
For doing that operations, I used {fillna()} and {drop_duplicates()}.
Now after doing this, I standardize the text columns, convert all heading into lowercase, trim spaces, use underscore, and fix data types by using some more functions of pandas library.
By doing all these operations now our data cleaning and prepration process is complete and now its time to save our processed data. And for that i used one more function of pandas i.e. {df.to_csv('filename.csv',index=False).
By doing all this my first task is completed. 
In the end I also compare the raw dataset and processed dataset so that other can see the difference between the datasets.
