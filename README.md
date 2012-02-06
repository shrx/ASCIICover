Asciicover
==========
Asciicover is a simple bash script to display the album art of a currently playing song in a terminal window.
This is done using libcaca's image conversion tool, img2txt.

![Screenshot](http://i.imgur.com/4L5FC.png)

Prerequisites, dependencies
---------------------------
You need to have libcaca installed for this script to work.

Usage
-----
Run the script when you want to see the album art of the current song that is playing in mpd.

The script will show the album's cover image if there's a file named `folder.jpg` in the song's directory.

As of now, you can terminate the script by two commands: `Ctrl+C` or `q+Return`.