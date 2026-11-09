Put the music files for the website in this folder (MP3 works everywhere).

Then open index.html, find "MUSIC SETTINGS" near the bottom, and list the
file names in PLAYLIST, for example:

  var PLAYLIST = [
    'assets/music/song-1.mp3',
    'assets/music/song-2.mp3'
  ];

The songs play in that order and repeat. The music button only appears on
the site once at least one listed file is found.
