# Music File Maker

[![GitHub issues](https://img.shields.io/github/issues/Naereen/StrapDown.js.svg)](https://GitHub.com/Naereen/StrapDown.js/issues/)
[![GitHub pull-requests](https://img.shields.io/github/issues-pr/Naereen/StrapDown.js.svg)](https://GitHub.com/Naereen/StrapDown.js/pull/)
[![Only 32 Kb](https://badge-size.herokuapp.com/Naereen/StrapDown.js/master/strapdown.min.js)](https://github.com/Naereen/StrapDown.js/blob/master/strapdown.min.js)

#### Tired of downloading mp3 files and adding tags? Try using this automatic music file maker!

## Features
- Downloads mp3 file from YouTube
- Adds track tags including title, artist, album, album art, and lyrics automatically
- Completely free, you don't need any paid api keys (only free ones)

## How to use

### Prerequisites
- [Node.js](https://nodejs.org)
- [npm](https://www.npmjs.com/)
- [git](https://git-scm.com/)
- [ffmpeg](https://ffmpeg.org/download.html) (download and unzip at root)
- [Last.fm API key](https://www.last.fm/api)
- [YouTube Data API v3 key](https://console.cloud.google.com/marketplace/product/google/youtube.googleapis.com?q=search&referrer=search)

### Step 1
At your console:
```bash
$ git clone
$ cd Music-File-Maker
$ npm install
```
If you want, you can just download this repository instead of using ``git``.

### Step 2
Create a file named ``options.json`` at root.
```json
{
    "youtubeKey": "youtube-api-key-here",
    "lastFmKey": "last-fm-api-key-here",
    "ffmpegPath": "path-to-ffmpeg-exe-here" 
}
```

### Step 3
At your console:
```bash
$ node index.js
```
Now you're ready to use this program!
