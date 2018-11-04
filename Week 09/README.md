# This Project

## Flipped Material


## Flipped Material

- Sign into [Datacamp](https://www.datacamp.com/)
- Complete [Working with Web Data in R](https://campus.datacamp.com/courses/working-with-web-data-in-r/downloading-files-and-using-api-clients?ex=1)
- Complete [Webscraping in R from PHP 2560](https://campus.datacamp.com/courses/php-15602560-statistical-programming-in-r).


## Exercises

1. Read the HTML content of the following URL with a variable called webpage: https://money.cnn.com/data/us_markets/ At this point, it will also be useful to open this web page in your browser.
2. Get the session details (status, type, size) of the above mentioned URL.
3. Extract all of the sector names from the “Stock Sectors” table (bottom left of the web page.)
4. Extract all of the “3 Month % Change” values from the “Stock Sectors” table.
5. Extract the table “What’s Moving” (top middle of the web page) into a data-frame.
6. Re-construct all of the links from the first column of the “What’s Moving” table.
Hint: the base URL is “https://money.cnn.com”
7. Extract the titles under the “Latest News” section (bottom middle of the web page.)
8. To understand the structure of the data in a web page, it is often useful to know what the underlying attributes are of the text you see.
Extract the attributes (and their values) of the HTML element that holds the timestamp underneath the “What’s Moving” table.
9. Extract the values of the blue percentage-bars from the “Trending Tickers” table (bottom right of the web page.)
Hint: in this case, the values are stored under the “class” attribute.
10. Get the links of all of the “svg” images on the web page.
