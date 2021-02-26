# Scrapping-Social-Media
Reddit/Twitter/Yahoo


## Features

Download Reddit/ Twitter saved posts (the scripts allow account for time_limit api calls)


Download Vantage_api/ Stocks/Cryptocurrencies and saved them in a pandas **df** format
View by categories

Download or clone repository
        Install Python 3 and run pip[3] install -r requirements.txt
        Install praw and 

To generate credentials:
Visit this url: https://www.reddit.com/prefs/apps/
Create a new app, name it, select "script"
Optionally add description and "about" url
Can use this as "redirect" url: http://www.example.com/unused/redirect/uri
Save the app, copy the public key under the app name and the secret key into config.py
User-agent can be something like "Saved posts scraper by /u/[your_username]"
Fill in your username and password
Run the file with python[3] redditsave.py
Optionally, run redditsave.bat if the above does not work
Check for folder named "Redditsaved" in Downloads
Browse using the landing page

