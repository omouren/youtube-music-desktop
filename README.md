# Youtube Music for Desktop
[![Build Status](https://travis-ci.org/omouren/youtube-music-desktop.svg?branch=master)](https://travis-ci.org/omouren/youtube-music-desktop)

A desktop app for [Youtube Music](https://music.youtube.com). This desktop app is supported by both [Nativefier](https://github.com/jiahaog/nativefier) and [Electron](https://github.com/electron/electron).

The Mac, Windows, and Linux apps can be downloaded from the [latest release](https://github.com/omouren/youtube-music-desktop/releases).

## Purpose
The purpose of this project is to build dedicated desktop apps for Youtube Music and leverage your OS's built in notification system.

This desktop app is not an official product of Youtube or Google and I am not affiliated with Youtube or Google in any way.

## Rebuilding the app
Requires `node`

### Nativefier
Install nativefier and make sure to have your [optional dependencies](https://github.com/jiahaog/nativefier#optional-dependencies) set up to replace the icon.
```
npm install -g nativefier
```

### Mac
```
nativefier --platform "mac" --icon youtube-music-logo.png --name "Youtube Music" "https://music.youtube.com" --honest --disable-dev-tools --single-instance --tray
```

### Windows
```
nativefier --platform "windows" --icon youtube-music-logo.png --name "Youtube Music" "https://music.youtube.com" --honest --disable-dev-tools --single-instance --tray
```

### Linux
```
nativefier --platform "linux" --icon youtube-music-logo.png --name "YoutubeMusic" "https://music.youtube.com" --honest --disable-dev-tools --single-instance --tray
```
