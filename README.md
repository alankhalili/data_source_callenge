# data_source_callenge
Module 6
##Overview:
The objective of this challange was to extract a list of movies from the NYT movie reviews and create a list of movies that has the word "love" in the headline.

We then took that list and pulled the movie_id from the movie data base.com.  From that, we obtained the detaled data about the movies.
We when combined the data from both the NYT and TMDB into a dataframe where we cleaned up the columns and exported it to a csv file.

##Dependencies:
1. We needed an API key for both the NYT and TMDB.
2. There were several situations I requested the help of both:
    a. TAs for the nested loop (e.g... genres queiry)and 
    b. ChatGPT some coding support and debugging.
    
##Challenges:
1. constructing the url to query the api without violating the api's rules
2. constructing loops to :
    a. query TMDB with the initial list of movies
    b. query the TMDB with the movie IDs
    c. extract and append specific pieces of data, some of which required thier own for x in y loops to extract dictionaries within a dictionary'

