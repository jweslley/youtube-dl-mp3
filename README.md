# youtube-dl-mp3

Downloads videos from YouTube and convert them to mp3.

## Installation

Just copy the `youtube-dl-mp3` script to somewhere in your `$PATH` (try /usr/local/bin).

## Requirements

  * [youtube-dl](https://github.com/rg3/youtube-dl)
  * wget
  * ffmpeg
  * lame

On Ubuntu, these requirements can be installed using this comand:

    apt-get install youtube-dl wget ffmpeg lame

## Usage

    youtube-dl-mp3 "video-url"


Example:

    youtube-dl-mp3 "http://www.youtube.com/watch?v=0714IbwC3HA"


You also can download all songs from a playlist at once:

    youtube-dl-mp3 "http://www.youtube.com/playlist?list=PL35104532FCBAE989"


## Bugs and Feedback

If you discover any bugs or have some idea, feel free to create an issue on GitHub:

<https://github.com/jweslley/youtube-dl-mp3/issues>


## License

MIT License. Copyright (c) 2012 [Jonhnny Weslley](<http://www.jonhnnyweslley.net>)
