# Netflix_Movies_and_Tv_shows_Clustering

# Objective:
The project's main goal is to create a model that can perform Clustering on comparable material by matching text-based attributes.

# Problem Statement:
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. In this project, you are required to do 

1. Exploratory Data Analysis
2. Understanding what type content is available in different countries.
3. Is Netflix increasingly focused on TV rather than movies in recent years?
4.  Clustering similar content by matching text-based features.

# Data Summary:
The dataset contains following columns:

● Show id: Unique ID for every Movie / TV Show

● type – Identifier - A Movie or TV Show

● title – Title of the Movie / TV Show

● director-director of the content

● cast –Actors involved in the movie / show

● country – Country where the movie / show was produced

● date_added – Date it was added on Netflix

● release_year – Actual Release year of the movie / show

● rating – TV Rating of the movie / show

● duration – Total Duration - in minutes or number of seasons

● listed_in – genre

● description – The Summary description

# Introduction:
Netflix’s recommendation system helps them increase their popularity among service providers as they help increase the number of items sold, offer a diverse selection of items, increase user satisfaction, as well as user loyalty to the company, and they are very helpful in getting a better understanding of what the user wants. Then it’s easier to get the user to make better decisions from a wide variety of movie products.

# Steps Involved:
1. EDA
2. Data Preprocessing
3. Handling Missing values
4. Duplicate value Treatment
5. K-Means Clustering
6. Hierarchical Cluster

# Conclusions:
1. There are about 70% movies and 30% TV shows on Netflix.
2. In this context, we've noticed that Netflix is increasingly focusing on movies rather than TV shows, especially after 2014.
3. We have also defined different clusters based on their content; we've defined 5 clusters and implemented the KMEANS clustering algorithm. We've  also imported the Silhouette Visualizer which displays the silhouette coefficient for each sample on a per-cluster basis, visualizing which clusters are dense and which are not.
4. After applying “K – means” optimal value of number of clusters is''5".
5. Silhouette score for a set of sample data points is used to measure how dense and well-separated the clusters are.
