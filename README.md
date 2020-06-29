# Web-Programming-Web-Requests
Assignment 3 of Bethel University Fall 2019's Web Programming course

In this project I make several different web requests to a server using javascript.
The server endpoint is hosted by Azure, but my code does not contain any server-
side code for this project. In this project I:
- Create an HTML web page that contains a form. The form contains 3 fields:
   first name, last name, and favorite Star Wars character. There are also
   3 buttons at the bottom with the values "Force Push" (for POST requests),
   "Force Pull" (for GET requests), and "Force Read" (for GET requests from
   a random index of already pushed data.
   JSON key/value format: {FirstName: *, LastName: *, Character: *}
- Create a second form on the page with a text box labeled "View Data" and two
   buttons labeled "Force Insight" (for loading the veiws data for the last
   character that was "Force Read") and "Watch Movies" (which posts the data from
   the "View Date" form to the endpoint /favoriteCharacters/{index}/views.
