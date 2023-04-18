# Netflix-Movies-and-TV-Shows-Clustering---Unsupervised
The goal of this project is to classify/group the Netflix shows into certain clusters such that the shows within a cluster are similar to each other and the shows in different clusters are dissimilar to each other.

# Data Description

##- <b>Dataset</b> - data_mobile_price_range.csv

- show_id : Unique ID for every Movie / Tv Show
- type : Identifier - A Movie or TV Show
- title : Title of the Movie / Tv Show
- director : Director of the Movie
- cast : Actors involved in the movie / show
- country : Country where the movie / show was produced
- date_added : Date it was added on Netflix
- release_year : Actual Releaseyear of the movie / show
- rating : TV Rating of the movie / show
- duration : Total Duration - in minutes or number of seasons
- listed_in : Genere
- description: The Summary description


# Steps we performed

- Importing the libraries
- Treating Null values
- Exploratory Data Analysis - EDA
- Natural Language processing
    - Removing Stop words
    - Removing Punctuation
    - Lemmatization
    - Tokenization
- Modelling
    - K Means clustering
    - Agglomartive clustering (Hirarichical Clustering)


# Conclusion
- From elbow and sillhoute score ,optimal of 26 clusters formed , K Means is best for identification than Hierarchical clustering as the evaluation metrics also indicates the same, in kmean cluster 0 has the highest number of datapoints
and evnly distributed for other cluster.
- Netflix has 5377 movies and 2400 TV shows, There are more numbers of movies (69.14%) than TV shows (30.86%) in the dataset.

- TV-MA has the highest number of ratings for Movies and TV shows.
- Around 50% of shows on Netflix are produced for adult audience. Followed by Teens, older kids and kids. Netflix has the least number of shows that are specifically produced for teenagers than other age groups.


- Highest number of movies released in 2017 and 2018
- Highest number of Tv Shows released in 2020
- The number of movies on Netflix is growing significantly faster than the number of TV shows.
- We saw a huge increase in the number of movies and television episodes after 2015.
- There is a significant drop in the number of Tv Shows/Movies after 2020(in year 2021), maybe due to covid.
- It appears that Netflix has focused more attention on increasing Movie content than TV Shows. Movies have increased much more dramatically than TV shows
- From October to January, maximum number of movies and TV shows were added on netflix.

- Documentaries are the top most Movie genre in netflix followed by standup comedy and Drams and international movies.

- kids tv is the top most TV show genre in netflix.

- Most of the movies have duration of between 50 to 150

- Highest number of tv_shows consistig of single season

- US and India are top 2 countries where Netflix is popular.

- United states has the highest number of content on the Netflix ,followed by india ( Movies are doubled or more than Tv shows)

- But for UK and Japan Tv shows are more added on netflix than Movies.
- India has highest number of movies in netflix followed by Egypt, Turkey and US.
- In India Target age group is "Teens" for netflix who watched more content than other traget age group.

- But For US, UK, France , Spain the target age group is "Adult".

- for Japan Teens and Adults are equally traget ages.
- Those movies that have a rating of NC-17 have the longest average duration.

- 30% movies released on Netflix, 70% movies added on Netflix were released earlier by different mode.

- Alastair Fothergill has directed three TV shows, the most of any director.
- Only six directors have directed more than one television show.

