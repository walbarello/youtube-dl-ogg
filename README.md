# youtube-dl-ogg

Downloads videos from YouTube and convert them to ogg.

## Installation

Just copy the `youtube-dl-ogg` script to somewhere in your `$PATH` (try /usr/local/bin).

## Requirements

  * [youtube-dl](https://github.com/rg3/youtube-dl)
  * wget
  * ffmpeg
  * lame

On Fedora or other GNU/Linux, these requirements can be installed using this comand:

	yum install youtube-dl wget ffmpeg lame

## Usage

    youtube-dl-ogg "video-url"


Example:

    youtube-dl-ogg "http://www.youtube.com/watch?v=0714IbwC3HA"


You also can download all songs from a playlist at once:

    youtube-dl-ogg "http://www.youtube.com/playlist?list=PL35104532FCBAE989"


