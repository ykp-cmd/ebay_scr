# Scraping of data on shopping sites.
This repo is dedicated to python scraping.\
Using BeautifulSoup4 refered to as bs4, I was able to streamline the process of checking for bad reviews of a product I wanted on a shopping site, which helped me make a decision on whether or not to purchase the product.\
The code used the BeautifulSoup module to parse an html string to find information about an item. It searches for items that contain any of the words in the list 'matches' and prints the item and the previous element. For  instance, if the list matches contains 'mirror', 'tray', and 'ceramic', it will search the html string for any of those words and print the item containing it and the preceding element.
