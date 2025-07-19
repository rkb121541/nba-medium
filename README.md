# NBA Web Scraping

I did some NBA web scraping from [basketball-reference.com](https://www.basketball-reference.com/) using these Medium articles as reference:

* [Web Scraping NBA data with Pandas, BeautifulSoup Part 1](https://medium.com/analytics-vidhya/web-scraping-nba-data-with-pandas-beautifulsoup-and-regex-pt-1-e3d73679950a)

* [Web Scraping NBA data with Pandas, BeautifulSoup Part 2](https://medium.com/analytics-vidhya/web-scraping-nba-data-with-pandas-beautifulsoup-and-regex-pt-2-fa0e4c1a16fa)

I ran into some 429 errors because of how many requests I was sending, so currently the outputs are messed up. I added `time.sleep()` after every request to help with this. I will have to see if this fixes it.