# OceanLife Pro v4.0

Interactive beach simulation with physics sandbox. Built with Three.js.

## Features

### Water System
- **Mesh Mode**: Animated wave mesh with foam at shoreline
- **Circle Particle Mode**: 4,400 animated circular water droplets
- **Shore Foam**: Foam particles that move with the waves
- Water stays in the ocean area - doesn't overflow onto beach

### People
- Multiple body types and skin tones
- Activities: walking, standing, sitting, lying, **building sandcastles**
- Sandcastle builders animate: gather sand → fill bucket → place sand → sandcastle grows

### Beach Scene
- Beach towels, umbrellas, sandcastles
- Animated beach balls
- Palm trees with coconuts
- Rocks on the shore

### Physics Sandbox
- **Drop Box**: Drop random colored boxes into the scene
- **Drop Sphere**: Drop spheres that bounce and roll
- **Object Weight**: Heavier objects fall faster, lighter objects float
- **Object Scale**: Adjust size of dropped objects
- **Clear Objects**: Remove all physics objects

### 3D Model Import
- **Import GLB/GLTF**: Load your own 3D models
- **Import OBJ**: Load OBJ files
- **Model Scale**: Adjust imported model size
- **Model Weight**: Adjust physics weight
- **Drop Model**: Drop copies of your imported model with physics

### Environment
- Dynamic time of day (24-hour cycle)
- Sun position and sky colors change
- Presets: Morning, Noon, Sunset, Storm
- Flying birds

## Controls

- **Orbit**: Drag to rotate view
- **Zoom**: Scroll or pinch
- **Right-click**: Context menu

## Run

Open `index.html` in a browser, or serve locally:

```bash
python3 -m http.server 3000
# Open http://localhost:3000
```

## Browser Support

Requires WebGL. Works in Chrome, Firefox, Safari, Edge.
