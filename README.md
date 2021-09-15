# Twitter

<p>
    <img src="https://pbs.twimg.com/profile_images/1354502907643666435/CpGOlLK-_400x400.jpg" width="240" height="240" />
</p>

## Description

Web scraping project to access Twitter throught the tweepy API (Tweetpy API webpage [here](https://docs.tweepy.org/en/latest/)). It allows you to obtain information about your personal profile or about any other profile from its username. It also allows you to get the latest tweets published by the users you are following, the latest tweets from a particular user, the latest tweets containing a specific word or the latest tweets posted from a particular location.


## Requirements

In order to use the API, it is necessary to have a Twitter developer account to obtain the access keys. You can do it from [here](https://developer.twitter.com/en/apply-for-access). Once you have your account, you have to modify the file **config_twitter.py** with your consumer_key, consumer_secret, access_token and access_secret. It must be located in the same folder as the script.

## Results

- Your profile information or other profile information (searched by user name):
  - Profile ID
  - Name
  - Location
  - Created datetime
  - Profile image
  - Favs count
  - Followers
  - Following
  - Geolocation activated
  - Background image

- Tweets:
  - Date of posting
  - Tweet ID
  - User
  - Tweet text
  - Language
  - Retweet count
  - Fav count
  - Replay to ID (if the tweet has been a response)
  - Replay to name (if the tweet has been a response)
  - Coordinates (if activated)
  - Hastags 
  - URLs
  - User mentions
  - Images/Videos

All this information about tweets can be search in four different ways:
  - Get the last N tweets posted by users we are following
  - Get the last N tweets posted by an specify user searched by its username.
  - Get the last N tweets posted that contain a word.
  - Get the last N tweets posted from a location.
