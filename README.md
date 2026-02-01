# Neural Cosmic Particles

A fully functional, highly aesthetic 3D interactive web application in a single HTML file. This application features a real-time particle system that reacts to hand gestures captured via webcam, built with Three.js and MediaPipe.

## Features
- **3D Particle Engine**: 8,000+ particles with smooth shape morphing.
- **Hand Interaction**: Reacts to hand gestures (Open Hand vs Closed Fist) and position.
- **Glassmorphism UI**: Stylish translucent control panel.
- **Zero Build Tools**: Runs directly in the browser (via local server).

## How to Run
Due to browser security restrictions on webcam access, you cannot simply open the file directly. You must serve it.

### Python (Recommended)
```bash
python -m http.server 8000
```
Then open `http://localhost:8000`

### VS Code
Use the "Live Server" extension.
