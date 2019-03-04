# NewsScraper

This program scrapes news articles from the home webpage of the New York Times, and then the web page will be populated with news article titles, summaries of the articles, and urls to the article pages.  The article data is then stored in a database set up with mongoose, and therefore before the code is run mongod must be running before the "node server.js" is typed into the bash.

This program uses the inclass assignment 20-scraping-with-mongoose as a boilerplate, therefore there are several similarities between them, including the way they function.  The major changes are that NewsScraper extracts summaries as separate from the title, and also scrapes from nytimes website.

The scraping is performed by typing "/scrape" at the end of the url, and the updated homepage can be seen again by deleting "/scrape" from the end of the url after the scrape has been performed.

This assignment was meant to use handlebars and be deployed to heroku, however neither of those have been done at this time.

Future updates will be performed at later dates to have it match the standard outlined in the assignment instructions.

-Daniel O'Connell

Link to Portfolio :  https://dano5190.github.io/Bootstrap-Portfolio/