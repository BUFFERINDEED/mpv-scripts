# mpv-scripts
Scripts for [mpv](https://github.com/mpv-player/mpv)

## ~~autoload-sub-in-mka.lua~~
~~Work on issues [mpv-player/mpv#5132](https://github.com/mpv-player/mpv/issues/5132) and [mpv-player/mpv#2663](https://github.com/mpv-player/mpv/issues/2663).~~

Now not needed anymore. Solved by commit [mpv-player/mpv@80d43ee](https://github.com/mpv-player/mpv/commit/80d43ee4e692f13358f134c906ba2c5439ecde5f).

## autoloop.lua
Work on issue [mpv-player/mpv#5222](https://github.com/mpv-player/mpv/issues/5222).
Automatically loops files that are under a given duration (default 5 seconds).

## screenshot-to-clipboard.js
Work on issue [mpv-player/mpv#5330](https://github.com/mpv-player/mpv/issues/5330).
Generates a temp screenshot file on desktop then copy to clipboard. (Windows only)

## save-sub-delay.lua
This script saves the sub-delay quantity for each file. When next time the file is opened, sub-delay is automatically restored.

## exit-fullscreen.lua
If you use `--keep-open=yes`, this script exits fullscreen mode when the playback reaches the end of file/playlist.
