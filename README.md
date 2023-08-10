# imdb_web_scraping
Using Beautiful soup Library from Python and HTML Tags to web scrape top 50 rated movies of all time, together with their rating and year of release, 

## IMDb Top 50 Movies with the most number of votes
This is a simple web scraper built to extract data from the IMDb website's top movies page. The webpage lists the top 50 movies with the most number of votes along with details such as release date, runtime duration, cast, genre, ratings, and more.

## step 1 
Reading: The scraper reads the HTML content of the IMDB webpage using Python's requests library.

## step 2 
The BeautifulSoup library is used to parse and beautify the HTML code, making it more understandable and easier to work with.

## step 3 
The required movie-related information, title and rating are  is extracted from the webpage by identifying the relevant HTML tags assocuated with the required information. 

## step 4 
The extracted data is transformed into a structured format, such as a CSV file, making it easy to store, analyse or share the data.

## step 5 
The script will generate a CSV file named "imdb_webscrapes.csv" containing the extracted data. It will include columns such as title and rating for each of the top 50 movies with the most votes.

## Source
http://www.imdb.com/search/title?sort=num_votes,desc&start=1&title_type=feature&year=1950,2012
