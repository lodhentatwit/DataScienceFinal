# DataScienceFinal
Exploring a dataset focused on sleep health and lifestyle to identify significant correlations and glean valuable insights.
 
## Draft Intro
The film industry is both lucrative and fiercely competitive. In this project, I aim to analyze IMDb's (Internet Movie Database) top 250 movies database, last updated approximately 10 months ago. This analysis aims to explore potential correlations that contribute to a movie's popularity, financial success, and general crtic rating. The three central questions I will research are: What is the rating distribution of the top 250 movies? Which genres are most prominent? And finally, which age rating category encompasses the highest number of movies within the top 250? I hope that these findings unveil compelling correlations and aid in the analysis of upcoming future movies.

## The Dataset
The dataset, sourced from Kaggle and published by Chidambara Raju, it was last updated a 10 months ago. Each entry within the CSV file comprehensively details a movie's rank, name, year, rating, genre, age rating, length, budget, global box office revenue, cast, director, and writer. Extracted from www.imdb.com, one of the largest online databases for movies and television shows, the IMDb rating within the dataset serves as a widely accepted benchmark for gauging the popularity and success of a movie.

Link: https://www.kaggle.com/datasets/rajugc/imdb-top-250-movies-dataset/data
 
## Methodology
The primary programming language for this analysis is Python, with the open-source Jupyter notebook serving as the integrated development environment (IDE). Within the Python ecosystem, key libraries such as Matplotlib, Seaborn, and Pandas will be used. These libraries facilitate data cleaning, efficient organization, extraction of essential information, and the seamless creation of informative graphs. 

The 3 questions:
1. What is the rating distribution of the top 250 movies?
   
   ![1](https://github.com/lodhentatwit/DataScienceFinal/assets/59703987/534860e5-5a2c-490d-abb5-53380afa802a)
 
   The chart illustrates that among the top 250 ranked movies, a significant portion received a rating of 8.1 on IMDb's 1-10 scale, with 10 being the highest rating. The highest-rated movie was "The Shawshank Redemption," with a score of 9.3. Upon closer examination of the graph, it is notable that only two movies had a rating of 9.0, while three movies obtained the lowest rating of 8.0.

3. Which genres are most prominent?
   
   ![2](https://github.com/lodhentatwit/DataScienceFinal/assets/59703987/fd7908f3-7625-468e-8ee1-724cad7b1ec2)

   Before analyzing the graph, it's essential to acknowledge that the majority of films undergo an  evaluation to determine their audience appropriateness. The 4 main age rating categories are G - general audiences; PG - parental guidance suggested; PG-13 - parents strongly cautioned; and  lastly R - restricted to those over 17.

   In general society groups movies as a kids activity, which would cause the types of age ratings to be around G and PG. Contrarily, the data reveals that 45% of the top 250 movies are categorized as "R" rated. Another finding is that 11% of these top-ranked films have never obtained certification from The Motion Picture Association of America (MPAA).

5. Which age rating category encompasses the highest number of movies within the top 250?
   
  ![3](https://github.com/lodhentatwit/DataScienceFinal/assets/59703987/b379d31c-c5a0-4797-9bd4-2bd6dc353a10)

  The graph above shows the genre of all the top movies. There is one major outlier in the bar graph, over 170 movies out of the top 250 are drama-based. The least-watched movie genre is horror. Most of the movies in the database were also mixed in genre for example, "Inception" was categorized as an action, adventure, and sci-fi movie.

## Conclusion
When looking at the top 250 IMDb-rated movies there is a lot to unfold. The majority of the movies are rated 8.1/10 and  there was not a single movie with a perfect score. The lowest-rated movies were 8/10 and the highest was 9.3/10. Almost half of all the movies were age-rated to R, which meant the majority of the movies where meant for the adult audience. Lastly, the most popular genre within the top 250 movies was Drama. 
