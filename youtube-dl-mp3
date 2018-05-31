#!/bin/bash

# Check if xclip is installed and no argument are passed
if [ -x "$(command -v xclip)" ] && [ "$#" -eq 0 ] ; then
	youtube-dl --extract-audio --audio-format mp3 --audio-quality 0 --ignore-errors -o "%(title)s.%(ext)s" "$(xclip -o)"
else
	youtube-dl --extract-audio --audio-format mp3 --audio-quality 0 --ignore-errors -o "%(title)s.%(ext)s" "$@"
fi
