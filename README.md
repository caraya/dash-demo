
## Notes about the demo repository

The code in this repository is designed to accompany the post [Revisting video enconding: DASH](http://publishing-project.rivendellweb.net/revisiting-video-encoding-dash/) . To store the mp4 content, some of which is over 100mb in size, we've set the repo with [GIT LFS](https://git-lfs.github.com/) to handle the large files; this will get around Github's file size limitation.  

A brief summary of the files:

* [html5-video.html](html5-video.html) is a traditional HTML5 video tag using MP4, WebM and OGG video
* [index.html](index.html) uses the Shaka Player to play DASH video
* [dashjs.html](dashjs.html) uses Dash.js's MediaPlayerFactory method
* [dashjs2.html](dashjs2.html) uses Dash.js's traditional method

