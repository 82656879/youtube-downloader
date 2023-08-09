# Youtube Downloader 23

Youtube downloader that actually works.

### Features:
- Automatically chooses highest quality download.
- Fast & multi-threaded downloads.
- See live progress for downloads & rendering.
- Download video or audio exclusively.
- Built from ground up. This is NOT just a simple wrapper around youtube-dl.

### Compatibility (only tested on):
- Python3
- Linux

### External dependencies:
- FFMPEG installed on the system, for rendering.

### Usage:
```
yt <url>
yt <url> --video-only
yt <url> --audio-only
```

### Example:
```
user@localhost ❯ yt "https://www.youtube.com/watch?v=vuo8kD5zF5I"

Title:
    "Reel 2 Real feat. The Mad Stuntman - I Like To Move It (Official Video)"

Quality:
    480p

- Video download: 100 %
- Audio download: 100 %
--------------------------------------------
Rendering: 00:03:54 of 00:03:54

Completed: "/home/user/Downloads/Reel 2 Real feat. The Mad Stuntman - I Like To Move It (Official Video).mp4"

~ 45s
```
