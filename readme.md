## Background
This is a program to calculate and print a statement of a customer's charges at a video store. 
The program is told which movies a customer rented and for how long. 
It then calculates the charges, 
which depend on how long the movie is rented,
and identifies the type movie. 
There are three kinds of movies: regular, children's, and new releases. 
In addition to calculating charges, the statement also computes frequent renter points,
which vary depending on whether the film is a new release.

## New Requirement I
The statement is expected to be printed in HTML so that the statement can be Web enabled.
More details has been documented in CustomerTest.should_return_statement_in_html_format.
 
## New Requirement II
Now we want to add new kind of movies: Action.

For Action movie, if days rented longer than 2 days, we would like to make the total price double.
User will get 2 frequent renter points for each action movies. 
