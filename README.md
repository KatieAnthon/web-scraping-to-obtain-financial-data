# web-scraping-to-obtain-financial-data

Using beautiful soup I extracted historical share data from a web-page.

I used the request library to download the page and parsed the text into beautiful soup.

Once this was completed I was able to turn the HTML table into a pandas dataframe.

After this i was able to print out the dataframe, utlise the read_html function and convert the BeautifulSoup object into a string.

This process was then repeated for the amazon stock data.
