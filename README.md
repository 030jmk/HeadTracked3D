# HeadTracked3D

A web-based 3D viewer that uses your webcam to track head movement for an immersive "fish tank VR" experience. Move your head to look around 3D objects as if they were floating behind your screen!

## Features

- 🎥 **Head tracking** using MediaPipe face detection
- 📱 **Fish tank VR effect** - creates the illusion of 3D objects behind your screen
- 🎯 **Multiple 3D formats** - supports GLB, GLTF, and OBJ files
- 🖱️ **Mouse controls** - rotate objects when head tracking is disabled
- ⚙️ **Screen calibration** - adjust for different monitor sizes
- 🎮 **No installation required** - runs entirely in your browser

## Demo

Simply open `index.html` in any modern web browser that supports WebRTC (Chrome, Firefox, Safari, Edge).

## How to Use

1. **Open the file** in your web browser
2. **Click "Start Webcam"** to enable camera access
3. **Click "Start Tracking"** to begin head tracking
4. **Upload a 3D model** (optional) or use the default colorful cube
5. **Move your head** left/right/forward/back to see the 3D effect
6. **Adjust screen size** in the controls for better calibration

## Supported File Formats

- **GLB/GLTF** - Recommended format with materials and textures
- **OBJ** - Basic geometry (materials will be auto-generated)

## How It Works

The app uses:
- **MediaPipe Face Detection** for real-time head position tracking
- **Three.js** for 3D rendering
- **Asymmetric camera frustum** to create the fish tank VR illusion

As you move your head, the camera's viewing frustum adjusts to simulate looking through a window into 3D space.

## Browser Requirements

- Modern browser with WebRTC support
- Webcam access permission
- Hardware acceleration enabled (recommended)

## Tips for Best Experience

- **Sit 40-80cm** from your screen for optimal tracking
- **Good lighting** helps face detection accuracy
- **Calibrate screen size** in settings for realistic perspective
- **Try different 3D models** to see the effect in action

## Files

- `index.html` - Complete standalone application
