MUSIC FOLDER — Hotchkiss Chronoshii Character Roster
====================================================

Put your audio files in THIS folder, named exactly:

    kate.mp3        -> plays when you open Chronoshii Kate Ruzinaki
    herscherr.mp3   -> plays when you open The Crimson Herscherr
    stahlrose.mp3   -> plays when you open The Stahlrose

Keep this "music" folder in the SAME place as howl_database.html:

    howl_database.html
    music/
        kate.mp3
        herscherr.mp3
        stahlrose.mp3

NOTES
-----
* Lowercase names, and the .mp3 extension, exactly as written above.
* .ogg / .m4a / .wav also work — if you use one of those, open
  howl_database.html in a text editor, search for "const MUSIC"
  near the top of the script, and change the extension there.
* Volume defaults to 50% (medium). The slider and mute button are at
  the bottom of the sidebar; your setting is remembered next visit.
* Tracks loop automatically and cross-fade when you switch characters.
* If a file is missing, the sidebar will say so and the page still works.
