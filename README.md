This is my attempt to predict the 2024 AP NFL MVP award using a random forest regressor model and training data from 1996-2023.

I collected data using a web-scraping process (HTML files can be found in mvp, player, defense, and team folders) on mvp data, offensive and defensive statistics, and team data and cleaned and combined the data into a single csv file (stats.csv). A huge shoutout to pro-football-reference.com for organizing an outrageous amount of NFL data. Using the combined csv file, I used data from 1996-2023 to train a random forest regressor model which creates a series of decision trees and averages predictions from those trees to predict the AP NFL MVP for 2024.

Read more and view results here: https://amyqiao.com/post-4.html
