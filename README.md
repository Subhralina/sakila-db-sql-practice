# sakila-db-sql-practice
If you are done practising SQL on online platforms and want more of a taste on Entity Relationships, this repo is the right place for you.

Here is the link that will help you load the Sakila DB into your local SQL server:
https://github.com/jOOQ/sakila

You can find more about the DB in the README.md of the repo.

## Questions

* Which actors have the first name ‘Scarlett’
* Which actors have the last name ‘Johansson’
* How many distinct actors last names are there?
* Which last names are not repeated?
* Which last names appear more than once?
* Which actor has appeared in the most films?
* Is ‘Academy Dinosaur’ available for rent from Store 1?
* Insert a record to represent Mary Smith renting ‘Academy Dinosaur’ from Mike Hillyer at Store 1 today .
* When is ‘Academy Dinosaur’ due?
* What is that average running time of all the films in the sakila DB?
* What is the average running time of films by category? Why does this query return an empty set?
* Write a query to find the full name of the actor who has acted in the maximum number of movies.
* Write a query to find the full name of the actor who has acted in the third most number of movies.
* Write a query to find the film which grossed the highest revenue for the video renting organisation.
* Write a query to find the city which generated the maximum revenue for the organisation. 
* Write a query to find out how many times a particular movie category is rented. Arrange these categories in the decreasing order of the number of times they are rented.
* Write a query to find the full names of customers who have rented sci-fi movies more than 2 times. Arrange these names in the alphabetical order.
* Write a query to find the full names of those customers who have rented at least one movie and belong to the city Arlington.
* Write a query to find the number of movies rented across each country. Display only those countries where at least one movie was rented. Arrange these countries in the alphabetical order.
* Display the first and last names of all actors from the table actor.
*	Display the first and last name of each actor in a single column in upper case letters. Name the column Actor Name.
*	You need to find the ID number, first name, and last name of an actor, of whom you know only the first name, “Joe.” What is one query would you use to obtain this information?
*	Find all actors whose last name contain the letters GEN:
*	Find all actors whose last names contain the letters LI. This time, order the rows by last name and first name, in that order:
*	Using IN, display the country_id and country columns of the following countries: Afghanistan, Bangladesh, and China:
*	Add a middle_name column to the table actor. Position it between first_name and last_name.
*	You realize that some of these actors have tremendously long last names. Change the data type of the middle_name column to blobs.
*	Now delete the middle_name column.
*List the last names of actors, as well as how many actors have that last name.
* List last names of actors and the number of actors who have that last name, but only for names that are shared by at least two actors
*	Oh, no! The actor HARPO WILLIAMS was accidentally entered in the actor table as GROUCHO WILLIAMS, the name of Harpo’s second cousin’s husband’s yoga teacher. Write a query to fix the record.
*	Perhaps we were too hasty in changing GROUCHO to HARPO. It turns out that GROUCHO was the correct name after all! In a single query, if the first name of the actor is currently HARPO, change it to GROUCHO. Otherwise, change the first name to MUCHO GROUCHO, as that is exactly what the actor will be with the grievous error. BE CAREFUL NOT TO CHANGE THE FIRST NAME OF EVERY ACTOR TO MUCHO GROUCHO, HOWEVER!
*	You cannot locate the schema of the address table. Which query would you use to re-create it?
*	Use JOIN to display the first and last names, as well as the address, of each staff member. Use the tables staff and address:
*	Use JOIN to display the total amount rung up by each staff member in August of 2005. Use tables staff and payment.
*	List each film and the number of actors who are listed for that film. Use tables film_actor and film. Use inner join.
*	How many copies of the film Hunchback Impossible exist in the inventory system?
*	Using the tables payment and customer and the JOIN command, list the total paid by each customer. List the customers alphabetically by last name:
*	The music of Queen and Kris Kristofferson have seen an unlikely resurgence. As an unintended consequence, films starting with the letters K and Q have also soared in popularity. Use subqueries to display the titles of movies starting with the letters K and Q whose language is English.
*	Use subqueries to display all actors who appear in the film Alone Trip.
*	You want to run an email marketing campaign in Canada, for which you will need the names and email addresses of all Canadian customers. Use joins to retrieve this information.
*	Sales have been lagging among young families, and you wish to target all family movies for a promotion. Identify all movies categorized as famiy films.
*	Display the most frequently rented movies in descending order.
*	Write a query to display how much business, in dollars, each store brought in.
*	Write a query to display for each store its store ID, city, and country.
*	List the top five genres in gross revenue in descending order.
*	In your new role as an executive, you would like to have an easy way of viewing the Top five genres by gross revenue. Use the solution from the problem above to create a view. If you haven’t solved 7h, you can substitute another query to create a view.
*	How would you display the view that you created in 8a?
*	You find that you no longer need the view top_five_genres. Write a query to delete it.
	
