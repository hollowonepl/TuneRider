TuneRider	v0.4.      (c) 2025-2026 hollowone/oftenhide 
============================================================

A simple TUI audio player that can play MP3, FLAC, M4A  and
WAV files directly from your MacOs/Silicon terminal.
 
It comes with two small utilities:

mp3play (a 36kB  standalone executable) - that plays single
file with no ui or other interactivity 

tunerider (a 600kB standalone executable) - that comes with
file_browsing UI, kind of like Open Cubic Player  in MS-DOS
times (sort of)

Both  programs  can  be  considered a public domain with no 
warranties, support or responsibility from the author  over 
actual usage.

They just work, tho, for me (author),so if it does for you,
then enjoy.

You can try to contact me via hollowonepl@gmail.com

If message is interesting or valid points brought up, I may 
consider responding.
_______
-h1^ofh

===========================================================
V0.4 vs, V0.3 changes:
- fixed: pause/resume glitch after long pause 
- fixed: app hanging/stalling when you leave the folder 
  While playing and next tune is supposed to auto pick up. 
  App now remembers from which folder it plays and tries to 
  get next tune from that folder, regardless where user is 
  browsing now
- feature: audio visualiser (press v) and in visualise mode 
  changing colours (c) and style (b)
- feature: if audio file is embedding image for the album 
  It's decoded and rendered either as SIXEL/TGP or if 
  terminal doesn't support graphics, trying best to convert 
  graphics to ansi coloured ascii (try TAB on one and 
  then 'a')
===========================================================
V0.3 vs, V0.2 changes:
- fixed correct visual rendering in light/dark themes of
  the terminal (originally only tested against dark themes)
- added pause/resume for the current track (SPACEBAR key)
- added showing all available metadata (title/year/genre)
  for selected file (TAB key)
===========================================================
V0.2 vs. V0.1 changes:
- it can now continually play whole directories
- it shows metadata of currently played tune 
  (title/author/year/genre)
- few bugs related to folder access (broken links,symlinks)
  fixed, should be more stable to navigate across system
  even if you have limited rights
===========================================================
