ASCIICover
==========
ASCIICover is a simple bash script to display the album art of a currently playing song in a terminal window.
This is done using libcaca's image conversion tool, img2txt.

![Screenshot](http://i.imgur.com/4L5FC.png)

Prerequisites, dependencies
---------------------------
You need to have [libcaca][1] and [mpc][2] installed for this script to work. You also need to have [mpd][3] for playing music.

[1]: http://caca.zoy.org/wiki/libcaca
[2]: http://mpd.wikia.com/wiki/Client:Mpc
[3]: http://mpd.wikia.com/wiki/Music_Player_Daemon_Wiki

Usage
-----
Run the script when you want to see the album art of the current song that is playing in mpd.

The script will show the album's cover image if there's a file named `folder.jpg` in the song's directory.

You can use the option `-r` to resize the window to a square dimension automatically on script start.
As of now, you can terminate the script by two commands: `Ctrl+C` or `q`.