# OceanLife Pro v4.0

Hyperrealistic beach simulation built with Three.js featuring high-polygon models, dynamic lighting, and immersive ocean physics.

## Features

### Hyperrealistic Water
- **Mesh Mode**: 180×180 segment water mesh with 8-octave wave simulation
- **Circle Particle Mode**: 6,400 animated circular water droplets
- **Shore Foam**: 2,000 particle foam system that moves with the waves
- **Dynamic Colors**: Water color changes based on depth and wave height

### High-Poly People (500+ polygons each)
- Detailed body parts: torso, head, arms, hands, legs, feet
- Facial features: eyes, nose, mouth, ears
- 4 hair styles: short, long, curly/afro, bald
- 8 realistic skin tones
- 5 body types: athletic, average, slim, stocky, child
- Male and female swimwear variations

### Activities & Poses
- Walking (with limb animation)
- Standing
- Sitting (on beach)
- Lying (sunbathing)

### Beach Scene
- Realistic sand with dune variations
- Wet sand near waterline
- 8 palm trees with coconuts
- 12 beach towels (varied colors)
- 8 beach umbrellas
- 5 sandcastles with towers
- 6 animated beach balls
- Rocks scattered on shore

### Environment
- Dynamic time of day (24-hour cycle)
- Sun position follows time
- Sky/ambient/fog colors shift realistically
- Night mode with stars
- 5 flying birds with wing animation
- 4K shadow maps

### Controls
- Orbit: drag to rotate view
- Zoom: scroll or pinch
- Right-click: context menu (add person, create wave, spawn beach ball)
- Control panel: adjust waves, people count, time of day, presets

## Run

Open `index.html` in a modern browser (Chrome, Firefox, Safari, Edge).

Or serve locally:
```bash
python3 -m http.server 3000
# Open http://localhost:3000
```

## Performance Modes

- **Ultra (Mesh)**: Best visuals, 180×180 water segments, foam particles
- **Particle Physics**: 6,400 circular water droplets, lighter on GPU
- **Hybrid**: Mix of both modes

## Browser Support

Requires WebGL 2.0. Works best in:
- Chrome 90+
- Firefox 88+
- Safari 15+
- Edge 90+

## License

MIT License - Use freely for personal and commercial projects.
