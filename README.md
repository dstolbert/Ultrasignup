# Ultrasignup
A quick scrape of the ultrasignup site, a bit of a messy repo.

Scraping was done using the requests package and by formatting GET requests to hit various geolocations across the USA. Because the site limited the returned results of each request, I had to be semi-redundant in my geolocations to ensure I was not missing races (especially in states with large areas of land). Duplicates entries were dropped. I have not done too much with this data yet. 

Events have been categorized into seasons and I created interactive cholorpleth plots with Dash. Future plans are to add additional state data and perform clustering to identify the features of each state that make it a good/bad place to live for trail running!

