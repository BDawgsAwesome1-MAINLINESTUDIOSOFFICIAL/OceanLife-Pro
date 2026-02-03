# OceanLife Pro v1.0

Interactive beach simulation with physics sandbox. Built with Three.js by Mainline Studios.

## Features

### Water System
- **Mesh Mode**: Animated wave mesh with foam at shoreline
- **Circle Particle Mode**: Animated circular water droplets
- Water reacts to objects and people with ripples

### People (50+ Animations)
- Walking, running, jogging, skipping
- Swimming, splashing, wading
- Building sandcastles, digging sand
- Sunbathing, relaxing, meditating
- Dancing, stretching, yoga poses
- Automatic activity changes every 3-15 seconds
- Always-alive idle animations (breathing, swaying)

### Physics Sandbox
- Drop boxes and spheres with adjustable weight/scale
- Heavy objects sink, light objects float
- Objects create splashes and ripples based on weight
- Import your own 3D models (GLB/OBJ)

### Controls
| Key | Action |
|-----|--------|
| W / ↑ | Move forward |
| S / ↓ | Move backward |
| A / ← | Strafe left |
| D / → | Strafe right |
| Q / Space | Move up |
| E / Shift | Move down |
| Mouse drag | Orbit camera |
| Scroll | Zoom |
| Right-click | Context menu |

### Environment
- Dynamic time of day (24-hour cycle)
- Presets: Morning, Noon, Sunset, Storm
- Flying birds

## Run

```bash
python3 -m http.server 3000
# Open http://localhost:3000
```

## Loading Screen
The app shows a Mainline Studios splash, then loads all assets with real progress indication before starting.

## Browser Support
Requires WebGL. Works in Chrome, Firefox, Safari, Edge.

---
*Made by Mainline Studios*
