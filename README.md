csgo_demos_animated_map
============
convert your CS:GO demo files to videos with radar view.

------------------------------

tasks
-------------
 - [x] Setup project
 - [x] Add demo analyzing library
 - [x] Add video analyzing library (ffmpeg probably)
 - [x] Create renderer for one tick
 - [x] Put everything together
 - [ ] Clean up
 - [ ] CLI
 
 May be
 - [ ] Add features?
 - [ ] Rewrite on other language?
 
install
-------

    npm install

Required for installation:

 - node 9
 - node-gyp ([installation](https://github.com/nodejs/node-gyp#on-windows))

If you get some error messages about build tools next command might be useful:

    ms build tools 2015 + npm config set msvs_version 2015 --global

build and run
--------

 Build:

    npm run build-ts

Watch build:

    npm run watch-ts

Run:

    npm start

useful links
---------

- [demofile github](https://github.com/saul/demofile/)
- [On-the-Fly Video Rendering with Node.js and FFmpeg](https://medium.com/@brianshaler/on-the-fly-video-rendering-with-node-js-and-ffmpeg-165590314f2))
