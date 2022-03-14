# Top Movie Data Exploration
### Faith Meyer

## Introduction
The most interesting thing I found in this data is that the highest grossing films have a lot of similarities in the type of movie that they are. They all have similar genres, ratings, and some come from the same distributer. Those aspects of a movie will be very important if you want a movie to do well. There are some exceptions in the rules, but a majority of hot ticket movies all fall into the same or have similar formulas when being made.

## Dataset
The data set I used is the Top 1000 Highest Grossing Movies. You can find the data here: [https://www.kaggle.com/sanjeetsinghnaik/top-1000-highest-grossing-movies?select=Highest+Holywood+Grossing+Movies.csv]
The data looks at the top 1000 movies and shows data on some of the different aspects of each movie, such as the rating, distributer, title, amount it made domestically and internationally, runtime, etc. The data was found from different sources such as IMDB, Rotten Tomatoes, and other movie detail sites that were not specified. I a interested in this data set because I am a big fan of going to movies and I am curious why certain movies and types of movies do better than others.

## Initial Questions
What initially drew me to this data set is the wide range of movies that were used and how there are movies from as early as the 1930s up to early this year. I was curious about if the reason certain movies did well was just because of the distributer, the franchise, the rating, or something completely different. While I was working with the data, I was wondering why Disney has been so successful with all of the movies they make? Does it have to with the fact that everyone knows about them and the nostalgia factor that people feel when watching their movies, or the types of movies they make, or something else.
When working with the data I did have to clean it up a bit. With this data set, some movies had more than one genre. I decided to separate out all of the genres into their own category and just focus on the first one, that way I would not have 1000 different genres to deal with and I only had a few main ones. I also cleaned up the runtime of the movies. I decided to keep the runtimes consistant by having them all be in minutes, that way it would be a bit easier to manage when creating the graphs. There also were parts of the data where information was missing, such as the rating, release time, or runtime, so I had to decide whether to keep those data points in or not. I decided to keep them in because when I looked at at some of the different sections that were complete, I would not have as much data to work with and the results might not give a full picture of what is going on.
I focused on a couple of questions when working with this data.
1. The first question I focused on is what types of things draw high sales for a movie? 
2. The other question I had is does the distributer of the movie really matter or do other aspects matter more to drive sales? 

## Discoveries & Insights

![RuntimevSales](/runtimevsales.png)
This graph shows the comparison of runtime vs total sales made for each movie. It shows that these two factors don't really relate to each other when it comes to a movie making a lot of money or not.

![RatingvSales](/ratingvsales.png)
This graph shows the rating of different movies vs total sales made. In this graph it shows how PG-13 and PG movies made the most money. There is the issue of the rating of the movie not being available, so the graph is not fully ocrrect, but overall it shows a trend that these two ratings are the most appealing and they tend to make a lot of money.

![Genrevsales](/genrevsales.png)
This graph is very telling about what helps a movie sell well. Every movie has a genre and this shows how well certain genres sell. This graph shows that Action movies are super popular and will make a lot of money. 

![RatingvGenre](/ratingvgenre.png)
This graph shows the relationship between the rating of the movie and the genre that it is. Looking at the data it makes a lot of sense that the two genres that are made for the most ratings are Action and Adventure since those are the two that made the most money according to the graph above. It also makes sense that they make a lot of them that are rated PG and PG-13 since those are the two most popular genres that people will see.

![Distributervsales](/distributervsales.png)
This graph looks at the different movie studios vs the amount of sales made. This graph will show if the distributer of a movie really matters when it comes to making money or not, and it looks like it does.

![DistributervRating](/distributervrating.png)
This graph shows the breakdown of rating vs distributer. We know that both of these categories really can affect the sales of a movie. If you look at the studios who do a lot of PG and PG-13 movies, they are the same ones who made more money on the graph of distributers vs sales.

![DistributervGenre](/distributervgenre.png)
This graph looks at the distributer vs genre. Just like the above graph we know that these two categories can also very much affect sales of a movie. If you look at the studios who do a lot of Action movies, they are the same ones who made more money on the graph of distributers vs sales.

![DistributervNumberofMovies](/distributervsnumberofmovies.png)
This graph looks at the breakdown of how many movies each studio has in the top 1000 highest grossing movies list. It shows that Walt Disney Studios doesn't have the most number of movies, but we know it does make the most money, as seen in an earlier graph. This brings up the question of why that is?

![Disneyrating](/disneyrating.png)
This graph shows the breakdown of all of the ratings that Disney movies in this list have. Most of them are unknown, but the largest two are PG and PG-13. Those are the two most popular genres for sales which will cause earnings for Disney movies to be high.

![Disneygenre](/disneygenrebreakdown.png)
This graph shows the breakdown of all of the genres that Disney movies in this list have. Disney makes a lot of Action and Adventure movies which causes their earnings to be very high as well.

## Conclusion
There are multiple categories that will impact the sales of a movie. These are categories such as Distributer, Genre, and Rating. There may be others that were not used for this data set though. If movie studios stick to the formula of using these elements to create a movie, then it will probably do very well in the box office.

## Sources
Data set: [https://www.kaggle.com/sanjeetsinghnaik/top-1000-highest-grossing-movies?select=Highest+Holywood+Grossing+Movies.csv]
