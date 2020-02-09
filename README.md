# SQL-movies
## Description 
In this project, I performed trivial SQL queries using SQLite implemented in python. The data is contained in multiple .csv files that have information on various movie data.

[Q01] List all the actors (first and last name) who acted in at least one film in the 80s (1980-1990, both ends inclusive) and in at least one film in the 21st century (>=2000). Sort alphabetically, by the actor's last and first name.

[Q02] List all the movies (title, year) that were released in the same year as the movie entitled "Rogue One: A Star Wars Story", but had a better rank (Note: the higher the value in the rank attribute, the better the rank of the movie). Sort alphabetically, by movie title.

[Q03] List all the actors (first and last name) who played in a Star Wars movie (i.e., title like '%Star Wars%') in decreasing order of how many Star Wars movies they appeared in. If an actor plays multiple roles in the same movie, count that still as one movie. If there is a tie, use the actor's last and first name to generate a full sorted order.

[Q04] Find the actor(s) (first and last name) who only acted in films released before 1985. Sort alphabetically, by the actor's last and first name.

[Q05] List the top 20 directors in descending order of the number of films they directed (first name, last name, number of films directed). For simplicity, feel free to ignore ties at the number 20 spot (i.e., always show up to 20 only).

[Q06] Find the top 10 movies with the largest cast (title, number of cast members) in decreasing order. Note: show all movies in case of a tie.

[Q07] Find the movie(s) whose cast has more actresses than actors (i.e., gender=female vs gender=male). Show the title, the number of actresses, and the number of actors in the results. Sort alphabetically, by movie title.

[Q08] Find all the actors who have worked with at least 7 different directors. Do not consider cases of self-directing (i.e., when the director is also an actor in a movie), but count all directors in a movie towards the threshold of 7 directors. Show the actor's first, last name, and the number of directors he/she has worked with. Sort in decreasing order of number of directors.

[Q09] For all actors whose first name starts with a T, count the movies that he/she appeared in his/her debut year (i.e., year of their first movie). Show the actor's first and last name, plus the count. Sort by decreasing order of the count.

[Q10] Find instances of nepotism between actors and directors, i.e., an actor in a movie and the director having the same last name, but a different first name. Show the last name and the title of the movie, sorted alphabetically by last name.

[Q11] The Bacon number of an actor is the length of the shortest path between the actor and Kevin Bacon in the "co-acting" graph. That is, Kevin Bacon has Bacon number 0; all actors who acted in the same movie as him have Bacon number 1; all actors who acted in the same film as some actor with Bacon number 1 have Bacon number 2, etc. List all actors whose Bacon number is 2 (first name, last name). You can familiarize yourself with the concept, by visiting The Oracle of Bacon.

[Q12] Assume that the popularity of an actor is reflected by the average rank of all the movies he/she has acted in. Find the top 20 most popular actors (in descreasing order of popularity) -- list the actor's first/last name, the total number of movies he/she has acted, and his/her popularity score. For simplicity, feel free to ignore ties at the number 20 spot (i.e., always show up to 20 only).

**The output of this program creates 12 .csv files with the data pulled from each SQL query**
