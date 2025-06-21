# Desperately Clingy Human Detector

A hilariously annoying AI that gets progressively more clingy the longer you stay on camera. Built with TensorFlow.js and the COCO-SSD model for real-time human detection.

## What it does

This web app uses your camera to detect humans and responds with increasingly desperate and clingy phrases. The longer you stay, the more unhinged it becomes!

### The 5 Stages of AI Clinginess:
- **Stage 1 (0-10 sec)**: Overly friendly
- **Stage 2 (10-20 sec)**: Getting weird  
- **Stage 3 (20-30 sec)**: Desperately clingy
- **Stage 4 (30-40 sec)**: Emotional manipulation
- **Stage 5 (40+ sec)**: Full meltdown!

## How to run

### Option 1: Simple local server
1. Download `index.html`
2. Start a local server:
   ```bash
   python -m http.server 8000
   ```
3. Open `http://localhost:8000/index.html` in your browser

### Option 2: With ngrok (for mobile testing)
1. Start local server (as above)
2. In another terminal:
   ```bash
   ngrok http 8000
   ```
3. Use the ngrok URL to access from any device

### Option 3: GitHub Pages
Just fork this repo and enable GitHub Pages - it'll work directly!

## Features

- Real-time human detection using TensorFlow.js
- Text-to-speech with escalating desperation
- Visual detection boxes around detected humans
- Responsive design for mobile devices
- Progressively annoying voice parameters
- Prevents you from leaving (tries to anyway!)

## Requirements

- Modern web browser with camera support
- Microphone permissions (for text-to-speech)
- Patience for an increasingly clingy AI

## Warning ⚠️

This AI will become emotionally attached to you. Use at your own risk. Side effects may include:
- Uncontrollable laughter
- Feeling guilty about closing browser tabs
- Questioning your life choices
- Temporary fear of AI uprising

---

*Built as a terrible idea that somehow works. Enjoy responsibly!* 😂 