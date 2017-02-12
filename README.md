# youtube-dl-mp3

Downloads videos from YouTube and convert them to mp3.

> This script is not necessary since youtube-dl already provides audio extration out-of-the-box. More info  https://github.com/jweslley/youtube-dl-mp3/issues/6

## Installation

Just copy the `youtube-dl-mp3` script to somewhere in your `$PATH` (try /usr/local/bin).

## Requirements

  * [youtube-dl](https://github.com/rg3/youtube-dl)

On Ubuntu, these requirements can be installed using this comand:

    apt-get install youtube-dl

## Usage

    youtube-dl-mp3 "video-url"


Example:

    youtube-dl-mp3 "http://www.youtube.com/watch?v=0714IbwC3HA"


You also can download songs from a playlist at once:

    youtube-dl-mp3 --playlist-items 1-16 "https://www.youtube.com/watch?list=PL-kcLKhqCpgT6WwL3p16MvxJFUKv0NRdB"
    

## Bugs and Feedback

If you discover any bugs or have some idea, feel free to create an issue on GitHub:

<https://github.com/jweslley/youtube-dl-mp3/issues>


## License

MIT License. Copyright (c) 2012 [Jonhnny Weslley](<http://www.jonhnnyweslley.net>)
