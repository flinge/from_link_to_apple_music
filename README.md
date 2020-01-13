# Migrate playlist from any streaming service (Spotify, Google, etc.) to Apple Music

## Step 1. Create a text file with links to songs in _your original_ service.
In case of Spotify it can be done by selecting all songs in playlist in _the desktop app_ and copying/pasting them to a plain text file. Save the file with a meaningful name (it will become your Apple Music playlist name) to iCloud, Dropbox, or whatever you use to sync files between desktop and iOS.

## Step 2. Get the shortcut.
Install [From link to apple music](https://www.icloud.com/shortcuts/d0dcbe54f0614cf78b453ae563d297d3) shortcut on your iOS device.

## Step 3. Run the shortcut.
It will ask you for the file. Point it to the file you've saved. The shortcut will read links from the file line by line and try to add the song to Apple Music playlist named same as the file (it will create the playlist if it does not exist). 

## Attributions
It's working thanks to the great guys from [https://odesli.co](https://odesli.co/), their [API](https://github.com/songlink/docs/blob/master/api-v1-alpha.1.md) and [iOS shortcuts](https://github.com/songlink/docs/blob/master/ios-shortcuts.md) 🤘

[Getting list of links from Spotify](https://medium.com/dreamer-in-black/using-workflow-for-export-spotify-playlist-to-apple-music-729af5d7711f)

[Text to playlist shortcut](https://www.icloud.com/shortcuts/6de7ad1875384ce5a9ba977d48cdea50)

