# Netdlix movies Web Scraping with Beautiful Soup
Web scraping was performed using BeautifulSoup and other libraries to gather information about the top 100 movies on Netflix from Rotten Tomatoes' webpage. The script sends a GET request to the webpage URL and retrieves its content. BeautifulSoup with the lxml parser is used to parse the HTML content and extract movie links. The links are obtained from <a> tags with the class "article_movie_poster". An empty DataFrame is created to store movie information, including links, title, rating percentage, and year. Iterating through each movie link, the script sends another GET request to retrieve the movie page content. BeautifulSoup is used again to extract the movie title, rating percentage, and release year from the HTML. The movie information is appended to the DataFrame. Finally, the DataFrame is saved as a CSV file for further analysis or usage.
Beautiful Soup Running time: (102,34 s.)
