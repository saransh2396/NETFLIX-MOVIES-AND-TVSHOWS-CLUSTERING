# NETFLIX-MOVIES-AND-TVSHOWS-CLUSTERING
 Netflix is a popular OTT platform where there are so many contents to watch which are from a lot of countries and there are a lot of genres to watch. So, the goal is to predict clusters by similar content by matching text-based features which in our case is the description column which is a small plot summary of the contents.
This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine.
In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.




# Presentation
[Here is the Presentation](https://github.com/saransh2396/NETFLIX-MOVIES-AND-TVSHOWS-CLUSTERING/blob/main/netflix%20clustering.pdf)

# Summary
In this project our goal was to predict clusters by similar content by matching Text based features. Firstly, Null Values were handled, Data Manipulation, EDA, Hypothesis from EDA, Feature Engineering in which all handles, symbols, stop words, punctuations were removed from our description column in which description of the contents were there. After feature engineering the text was converted to a TFIDF sparse matrix using TFIDF Vectorizer and converted into an array. Now, the main task is to estimate the clusters which we got from Elbow Method and Silhouette’s score which was 20 and then the KMeans model implemented and then further, evaluated. After that we grouped our data according to the clusters.
