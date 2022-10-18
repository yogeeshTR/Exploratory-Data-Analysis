# Exploratory Data Analysis on  "US Credit-Card-Fraud" dataset which containing 5.5 million rows and 16 columns using pandas.

Introduction About Dataset

In this project analysis, we will analyze the US Credit-Card-Fraud Dataset from the Kaggle website. This dataset has over 5.5 million rows of data with 16 columns. This dataset contains legitimate and fraudulent transactions from the duration of 1st Jan 2019 - 31st Dec 2020. It covers credit cards of 1000 customers doing transactions with a pool of 800 merchants. The goal of this project is to get an overview and also a better understanding of US Credit-Card users' Fraud reasons by applying some data analysis & visualization skills to the real-world dataset.

#Here are the following steps that we need to follow:

**step 1:-** Importing Required libraries, Download a dataset from a Kaggle source and load the dataset into the panda's data frame.

**step 2:-** Feature Engineering (Perform any additional steps like parsing dates, converting Dtypes, creating additional columns, merging multiple datasets, etc.

**step 3:-** Open-ended exploratory data Analysis.

**step 4:-** Asking , Answering and Visualization, interesting questions.

**step 5:-** Conclusion, Summarizing inferences, and Future work.


**Conclusion**

 After downloading the dataset and doing some feature engineering we got a good dataset which is in a very clean and valuable data format we did some analysis on that data and get some useful insights from them they are as follows.

1. By encoding the categorical features in the dataset using count frequency encoding to convert them into valuable frequency value we found that the amount and fraud are highly correlated to each other.

2. Even though the fraud transaction is less in a dataset,The total means amount transaction the mean fraudulence amount is more than the mean non-fraudulence amount.

3.Interesting thing is more educated and the below less than 50 age group of people got more fraud count.

4.By analyzing the correlation between transaction hours and amount with respect to gender we found that up to 11 am Females card holders did more transactions compare to males after that there is a significant drop in the trend of female users. But after 9 pm Male cardholders do more transactions. one thing to notice here is Females feels safer carrying credit card rather than carrying cash.

5.Most of the fraud happens in Holiday seasons because at the end of the year merchants give more offers and attractive prices to trap the customers. even they may offer more to credit card users.

6.Most of the credit card usage is done during Gas_transport, and grocery_shopping but during analysis, we found that the fraudulent rate is also high in these categories only according to this dataset.

7.More credit card users state have a high fraudulent rate.

Finally, we conclude that fraudulence is depends more on the amount , frequent usage, gender, transaction hours in a day, month, and category



Check jupayter Note here : https://jovian.ai/yogeeshtr26/project-2-eda-on-credit-card-fraud-detection
