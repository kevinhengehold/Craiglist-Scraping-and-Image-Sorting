# Craiglist-Scraping-and-Image-Sorting
Scrape a set of craiglist pages for posts, continue checking those posts at a regular interval to scrape new posts, sort the images of those posts into similar groups.

Craigslist Prime Scraper should be run first - it collects all the items listed on the web pages listed in search_urls.

Then, at whatever frequency you desire, run Craigslist Difference Scraper to scrape the new items posted since the last time you ran the scraper.

To sort the imaages into similar clusters, run Grouping Similar Images. 
