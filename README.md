# VidJS 

## Introduction

VidJS is a simple and easy-to-use library that provides a custom videoplayer built on top of the html video element. It customises and extends the available controls. 

 ## Features

- **Playback Speed Control** 
    * Allow users to change the playback speed of videos.
- **Customizable Controls**
    * Use your own icons and colors with the Video Player.
- **Available Controls** 
    * Play/pause
    * mute/unmute
    * volume
    * fullscreen
    * exit fullscreen
    * draggable progress bar
    * scrub handle with live progress updates, etc.
- **Keyboard Shortcuts**
    * space - play and pause.
    * keyK - play and pause.
    * keyF - enter and exit fullscreen.
    * keyM - mute and unmute.
    * ArrowRight - fast forward.
    * ArrowLeft - rewind.
    * keyJ - fast forward.
    * keyL - rewind.
    * Numpad0 - bring back to start.
    * digit0 - bring back to start.
- **Events API**
    * Listen for events such as video near end to trigger custom behavior.

## Upcoming Features

- **Quality Control**: Allow users to change the quality of videos.
- **Subtitle Control**: Allow users to switch on or off subtitle of videos.

## Configuration

The player relies on **class selectors** for flexibility. You control structure and styling; the library handles behavior.

Examples:
- `.play-pause-btn`
- `.scrub-bar`
- `.volume-scrub-bar`
- `.settings-menu`   

This makes it easy to:
- Replace icons
- Animate controls
- Match your brand design

## Installation

You can install VidJS via npm:

```bash
npm install VidJS 
```   