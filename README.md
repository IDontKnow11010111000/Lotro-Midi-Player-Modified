# Lotro-Midi-Player-Modified
A Modified Version of the Lotro Midi Player

So... I basically, after troubleshooting, just changed the MIN_PLAYABLE and MAX_PLAYABLE (in the Note.java class(?)) to C0 and G9 respectivly, becase that was the most range I could get it to not crash on trying not at all to troubleshoot the problem.  Then, I changed some values (search for "Other change here" in Note.java), specifically the number in the if statment (3 to 4), the number in the for loop (3 to 4), and the number in the other for loop (4 to 5).  I did that because the resulting abc file seemed to be 1 octave too high, and this may have fixed it... I also commented out most of the features from the MainWindow.java file, some of which corrosponded to the game this was created for (local playback mode check box, what was the ingame chat (im assuming), and changing the instrument), and the transpose feature, because (I think at least) it was not designed to work with such a large range.

Um...  I think thats it... (well, I also added a string to the DrumMap.java file, iirc)...

So, here is a link to the post where (at least with a quick google search I found) the author posting some links:
https://forums.lotro.com/forums/showthread.php?121331-LotRO-MIDI-Player-and-MIDI-to-ABC-converter&s=3ea4bfcac2891ee83de3df1f20618925

Um, and also, here is the source code, just in case you want the origenal:
https://code.google.com/archive/p/lotromidiplayer/source
