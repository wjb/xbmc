script.cu.lrclyrics
===================

cu.lrclyrics is based on the cu and lrc lyrics scripts.

credits to everyone who worked on these scripts before:
EnderW, Nuka1195, Taxigps, amet, ronie, yannrouillard


the script first tries to find synchronised (lrc) lyrics.
if no lrc lyrics are available, it will continue to search for unsynchronised lyrics.


depending on which options you've enabled, the script searches for lyrics in this order:
- embedded lrc lyrics
- lrc lyrics file
- minilyrics scraper
- ttplayer scraper
- alsong scraper
- baidu scraper
- gomaudio scraper
- lyrdb scraper
- embedded text lyrics
- text lyrics file
- lyricwiki scraper
- lyricsmode scraper
- lyricstime scraper


when the scripts downloads lyrics through one of the scrapers,
you can optionally save them to a file for future use.


properties for other addons:
Window(Home).Property(culrc.lyrics)  - shows the current lyrics, including timing info in case of lrc lyrics.
Window(Home).Property(culrc.source)  - source or scraper that was used to find the current lyrics.
Window(Home).Property(culrc.running) - returns 'true' when the lyrics script is running, empty if not.
