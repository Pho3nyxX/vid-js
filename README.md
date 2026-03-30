# VidJS 

VidJS is a lightweight, customizable video player built on the HTML5 video element with enhanced controls. 

 ## Features

- **Custom Controls** – Fully replace and style your own controls.   
- **Playback Speed Control** – Adjust speed seamlessly.   
- **Full Player Control** – Play, pause, volume, fullscreen, and more.   
- **Draggable Progress Bar** – Smooth scrubbing with live updates.   
- **Keyboard Shortcuts** – Built-in shortcuts for better UX.   
- **Flexible Structure** – Control UI with your own HTML + CSS.   
- **Events API** – Hook into player events for custom behavior

## Upcoming Features

- **Quality Control**: Allow users to change the quality of videos.
- **Subtitle Control**: Allow users to switch on or off subtitle of videos.

 ## Available Controls

- Play / Pause
- Mute / Unmute
- Volume Control
- Fullscreen / Exit Fullscreen
- Draggable Progress Bar
- Scrub Handle with Live Updates

## Keyboard Shortcuts

| Key           | Action            |
| ------------- | ----------------- |
| `Space` / `K` | Play / Pause      |
| `F`           | Toggle Fullscreen |
| `M`           | Mute / Unmute     |
| `→`           | Fast Forward      |
| `←`           | Rewind            |
| `J`           | Fast Forward      |
| `L`           | Rewind            |
| `0`           | Restart Video     |

## Installation

```bash
npm install VidJS 
```   

## Customization

VidJS uses **class-based selectors**, giving you full control over structure and styling.

Example classes:

- `.play-pause-btn`
- `.scrub-bar`
- `.volume-scrub-bar`
- `.settings-menu`   

This allows you to:
- Replace icons
- Animate controls
- Design your own UI
- Match your brand design


## Events API

Listen to player events and trigger custom behavior.
