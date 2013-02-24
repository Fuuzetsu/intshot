intshot
=======

Little script to take screenshots of your videos using ffmpeg at specified intervals.

Currently it will not render subtitles due to ffmpeg limitations. An alternative is to use mplayer to take the screenshots (flag coming) or to render the whole video and then pick out frames (you don't want this).

I might figure out a hack to manually increase subtitle times so that they properly line up. We'll see.

See `python intshot.py -h` for help. Uses Python 2.
