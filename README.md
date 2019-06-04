# Analysis-of-Toronto-Neighborhoods-with-Python
Analysing all the neighborhoods in Toronto and Grouping them based on the venue categories located there

This is my attempt to learn about Data Analysis, Data Processing and Machine Learning and it is done as a part of IBM data science certification on Coursera. I have analysed the neighborhoods of Toronto and grouped them into clusters based on the types of venues located there such as Cafe, Park, Gym, Restaurant etc. 

Toronto Neighborhoods are gathered through scraping of Wiki page and their geospatial data is read from CSV file. Venue places located in each of those neighborhoods are obtained using Foursquare API call. With the use of One-hot encoding, type of venue (categorical data) column is converted into numerical columns as it helps in the application of machine learning algorithm. Based on the values of these numerical venue type columns and with K-means clustering, neighborhoods are divided into different groups/clusters. Each cluster consists of similar neighborhoods with their similarity based on the venue types present.

Please refer to comments in notebook for more clarity.
