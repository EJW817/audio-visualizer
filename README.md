# Real-Time Audio Visualizer

Live demo: https://ejw817.github.io/audio-visualizer/
## What this is

I built a browser-based audio visualizer that reacts in real time to any loaded track.  
It has two modes:

- **Header Bars** – responsive bar graph with fast attack and smooth decay  
- **Spiral + Heartbeat** – radial particle spiral with a center halo and heartbeat line

## How it works

- Uses the **Web Audio API** for real-time FFT analysis  
- Maps frequency bins into 48 bands  
- Applies **gamma correction** and a custom curve to shape perceived loudness  
- Uses **attack / decay smoothing** to emphasize transient peaks  
- Normalizes animation with `dt` so rotation and popping speed stay consistent across devices  
- Renders everything on an HTML5 **Canvas**

## Tech stack

- HTML  
- CSS  
- JavaScript  
- Web Audio API  
- Canvas API

## How to use

1. Open the live demo link.  
2. Load an audio file from your device.  
3. Press **Start Visualization**.  
4. Switch between modes using the Header Bars / Spiral buttons.
