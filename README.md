# paramount-dl
Bash script to download from Paramount+ using youtube-dl, retrying downloads when corruption occurs. English subtitles are also downloaded and muxed into an MKV with the video/audio.

This script looks for a links.txt file in the pwd containing a list of Paramount+ links, each on its own line.

Dependencies: youtube-dl, mkvmerge and mkvpropedit (included in mkvtoolnix-cli), mediainfo
