# botify-bot

PROCESS:

1. Created a python script called spotify.py that imports libraries like os, requests, json, WebClient and SlackApiError.
2. Created my app through Spotify and started process of getting API authentication.
3. API authentication only lasts 1 hour per access token, so I need to add code to the python script that calls for the token each time. 
4. I realized the code provided by spotify to get API access tokens is in javascript, so I found a library called Spotipy that utilized spotify API in python.