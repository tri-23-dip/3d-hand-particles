# 🤚 3D Hand Particles - Interactive Gesture Control

[![Three.js](https://img.shields.io/badge/Three.js-3D-green)](https://threejs.org/)
[![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-blue)](https://mediapipe.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A real-time interactive 3D particle system controlled by hand gestures through your camera. Watch as thousands of colorful particles respond instantly to your hand movements, changing shape and behavior based on different gestures.

![Demo Screenshot](https://via.placeholder.com/800x400/030614/0ff?text=3D+Hand+Particles+Demo)

## ✨ Features

- **🎮 Gesture Controls**
  - ✋ **Open Palm** - Default sphere mode
  - 👊 **Closed Fist** - Explosive star formation
  - 🤏 **Pinch Gesture** - Flowing wave motion
  - 👆 **Hand Position** - Move particles left/right/up/down
  - 📍 **Screen Zones** - Different shapes based on hand location

- **🔮 Multiple Particle Shapes**
  - ⚪ Sphere - Perfect uniform distribution
  - ❤️ Heart - Romantic parametric form
  - ⭐ Star - Five-pointed star formation
  - 🌀 Torus - Donut-shaped ring
  - 🌊 Wave - Undulating sinusoidal pattern

- **⚡ Performance Features**
  - 15,000+ particles with rainbow colors
  - 60 FPS real-time rendering
  - Fast particle interpolation (0.25 response speed)
  - GPU-accelerated hand tracking
  - Additive blending for glowing effects

## 🚀 Quick Start

### Option 1: Run Locally
```bash
# Clone the repository
git clone https://github.com/yourusername/3d-hand-particles.git

# Navigate to directory
cd 3d-hand-particles

# Open index.html in your browser
# Or use a local server
python3 -m http.server 8000
# Then visit http://localhost:8000