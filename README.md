# Lotro-Midi-Player-Modified
A Modified Version of the Lotro Midi Player

So... I basically, after troubleshooting, just changed the MIN_PLAYABLE and MAX_PLAYABLE (in the Note.java class(?)) to C0 and G9 respectivly, becase that was the most range I could get it to not crash on trying not at all to troubleshoot the problem.  I also commented out most of the features from the MainWindow.java file, some of which corrosponded to the game this was created for (local playback mode check box, what was the ingame chat (im assuming), and changing the instrument), and the transpose feature, because (I think at least) it was not designed to work with such a large range.

Um...  I think thats it... (well, I also added a string to the DrumMap.java file, iirc)...
