# Spotify_Playlist_Data
* Using Python, with the SQL Alchemy and Pandas libraries I have connected to the spotify API using another library called Spotipy.
## requirements
* Spotify Premium Account
## How to use
1. I have cleared out my personal "Client ID" and "Client Secret." You will need to obtain these two strings come from a personal Spotify account.
2. I have added a user-input for the playlist string that adds the playlist information into a pandas dataframe.(You retrieve the playlist string from Spotify)
3. There is an export-to-SQL line that exports the pandas dataframe to a local db if you would like to manipulate the data with SQL.
