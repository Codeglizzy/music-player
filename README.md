# Music Player

This is a simple music player put together to allow me to quickly access my library of music. 

# How it Works

You can either compile the solution in Visual Studio, or you can navigate to the `\bin\Release\net6.0-windows\` folder and launch the `SoundTest - Shortcut` executable. 

After launching (or compiling), you should see this screen:

![This is an Image](https://github.com/Codeglizzy/music-player/blob/main/SoundTest/interfaceExample.png?raw=true)

   
From here you need to click "Browse Directory" and navigate to the directory where you keep your music library. The name of the file will appear in the upper-right List Box, and the location of the file is stored accordingly in the lower-right List Box.

Here is what it will look like with music filled:

![This is another image](https://github.com/Codeglizzy/music-player/blob/main/SoundTest/filled_InterfaceExample.png?raw=true)

That is all for the hard stuff. 

From here on out, the program is fairly intuitive. Select a song from either of the list box panels on the right and click "Play Song"!

* The slider is the volume bar.
* The blue text box displays the selected song name.
* "Next" Will immediately jump to the next song in the browser.
* "Previous" Will restart the song after 5 seconds, but will jump to the previous song before 5 seconds.
* "Browse Directory" Displays the Folder Browser Dialog so you can easily navigate to your music.
* "Play Song" Plays the selected song.
* "Stop" Will stop the song currently playing.

### That's the Magic!

Let me know if you run into any issues not listed below!


# The Bad News

Here is a list of known issues/bugs that I'm working on:
* Only supports .wav and .mp3 files.
* Unable to resize window properly without disturbing other controls.
* Currently only able to browse 1 directory at a time.


