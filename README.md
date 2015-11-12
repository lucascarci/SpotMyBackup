# SpotMyBackup
Backup and Restore your Spotify Playlists and "My Music".

This javascript based app allows you to backup all your playlists and import them in any other Spotify Account. It uses the OAuth-Functionality of Spotify to be able to handle your personal playlists. 

In consequence, no credentials or data is stored or processed on the Webserver itself.

You can use it at www.spotmybackup.com or on your own webserver (see Q&A).

## Setup
* create new app https://developer.spotify.com/my-applications
* add your redirect URL in the settings "http://xxxx/login.html"
* copy the client id to index.html

## todo
* backup song name, artist, album and song order
* after generating the list put the blob link onto the download button
