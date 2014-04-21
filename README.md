#OMDB TAKE 3

###Assignment
____________________________________

For this assignment you will be creating an OMDB app one more time.  

However, this time, instead of using the OMDB API, you will be creating your own database of movies.  

You have been given a sinatra app with code to get you going, and methods to help you setup your database.  

You have also been given a working feature to add movies to the databse. There is a route `/movies/new` which renders a form to input new movie data. And a route to send this form to, and save the info to your database.  

###Phase One
_________________

**Add a search form on your search.erb page.**  
Remember to ask yourself, "where should this form go?"  

###Phase Two  
__________________

**Search for a movie in your database**  

1. Add a route to send your search form to
2. Add code that will seach for movies based on the title your user searched for
3. Add a view page to display these results

*Hint: Remember, that the results will be returned in an array.*  

**Display your results**  
Create a view page to view your results.  

###Phase Three
____________________

**Add a movies detail feature.**  
When your users click on a title it should take them to a page with details just for that movie.  

1. Add a new route for your details link to go to
2. Add some code in here that will look up a movie by it's id
3. Add a view page to display your movie details
