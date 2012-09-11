#!/bin/bash

url=$1

TMP_FILE="youtube-mp3-$RANDOM.tmp"

youtube-dl --ignore-errors --get-title --get-url --get-filename "$url" > $TMP_FILE 2> "/tmp/$TMP_FILE.err"

exec 42< $TMP_FILE

while read video_title <&42 ; do
  read video_url <&42
  read video_filename <&42
  wget "$video_url" -O "$video_filename"
  ffmpeg -i "$video_filename" "$video_filename.wav"
  lame "$video_filename.wav" "$video_title.mp3"
  rm -f "$video_filename" "$video_filename.wav"
done

exec 42<&-
rm -f $TMP_FILE
