ASCIICover
==========
ASCIICover is a simple bash script to display the album art of a currently playing song in a terminal window.
This is done using libcaca's image conversion tool, img2txt.

![Screenshot](http://i.imgur.com/ouXfu.png)

Prerequisites, dependencies
---------------------------
You need to have [libcaca][1] and [mpc][2] installed for this script to work. Libcaca must be compiled with imlib2 support. You also need to have [mpd][3] for playing music.

[1]: http://caca.zoy.org/wiki/libcaca
[2]: http://mpd.wikia.com/wiki/Client:Mpc
[3]: http://mpd.wikia.com/wiki/Music_Player_Daemon_Wiki

Usage
-----
Run the script when you want to see the album art of the current song that is playing in mpd.

The script will show the album's cover image if there's a file named `folder.jpg` in the song's directory.

You can use the option `-r` to resize the window to a square dimension automatically on script start.
If you want to manually refresh the script while running, for example if you added an image after you've already started playing the song, you can press `r`.
If you use [iTerm][4], you can also try the experimental option `-d` which enables the high-pixel-density mode by using a smaller font.
As of now, you can terminate the script by two commands: `Ctrl+c` or `q`.

[3]: http://www.iterm2.com