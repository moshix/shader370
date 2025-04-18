# WebGL Shader Visualizer

A dynamic WebGL shader visualization application with music playback capabilities. This project features 16 unique shader effects that create mesmerizing visual patterns synchronized with background music.

## Features

- 16 unique WebGL shader effects:
  1. Current flowing pattern
  2. Cosmic Nebula
  3. Dynamic Mandala
  4. Electric Field
  5. Wave interference with red theme
  6. Kaleidoscope with rainbow theme
  7. Dynamic Geometric Pattern
  8. Quantum Flux
  9. Liquid Crystal
  10. Aurora Dreams
  11. Neon Cityscape
  12. Ocean Depths
  13. Burning Mandelbrot
  14. Julia Spirals
  15. Water Caustics
  16. Psychedelic Swirl

- Music playback system with:
  - Random track selection
  - Mute/Unmute functionality
  - Skip track option
  - Track display
  - No repeat tracks until all have been played

- Interactive controls:
  - Left/Right arrow keys to cycle through effects
  - Automatic effect cycling every 30 seconds
  - Responsive canvas that adapts to window size
  - Click-to-start functionality for better audio experience

## Effect Descriptions

- **Current Flowing Pattern**: Electric current visualization with dynamic flow and color transitions
- **Cosmic Nebula**: Space-inspired effect with stars, nebula clouds, and cosmic dust
- **Dynamic Mandala**: Intricate geometric patterns that evolve and rotate with time
- **Electric Field**: Simulation of electric field lines with dynamic charge interactions
- **Wave Interference**: Red-themed interference patterns creating mesmerizing wave effects
- **Kaleidoscope**: Rainbow-colored kaleidoscopic patterns with smooth transitions
- **Dynamic Geometric**: Complex geometric patterns with rotating and scaling elements
- **Quantum Flux**: Hypnotic effect with layered, fractal-inspired patterns and pulsating color gradients
- **Liquid Crystal**: Beautiful fluid-like movement with prismatic colors that simulate liquid crystal displays
- **Aurora Dreams**: Northern lights-inspired effect with organic flowing patterns and starry background
- **Neon Cityscape**: Cyberpunk-inspired city with glowing neon signs, animated rain, and flying vehicles
- **Ocean Depths**: Enhanced underwater scene with bioluminescent jellyfish, dynamic caustics, and floating particles
- **Burning Mandelbrot**: High-detail Mandelbrot zoom with dynamic coloring and ember effects
- **Julia Spirals**: Dynamic Julia set with evolving spiral patterns and shifting colors
- **Water Caustics**: Realistic underwater light refraction patterns with shimmer effects
- **Psychedelic Swirl**: Mind-bending warping patterns with recursive distortions and vivid coloration

## Technical Details

- Built with vanilla JavaScript and WebGL
- Uses GLSL shaders for visual effects
- Implements a custom music player with track management
- Responsive design that works on any screen size
- User interaction required to start audio (for browser compatibility)
- High-performance shader implementations with dynamic quality scaling
- Custom favicon support

## Usage

1. Open `index.html` in a modern web browser
2. Click anywhere on the screen to start the visualization and music
3. Use the controls in the bottom-right corner to:
   - Mute/Unmute the music
   - Skip to the next track
4. Use left/right arrow keys to manually cycle through effects
5. Effects will automatically cycle every 30 seconds

## Performance Notes

- The Mandelbrot effect (Effect #13) features high-detail rendering with dynamic iteration counts
- Ocean Depths effect includes complex particle systems and multiple light sources
- All effects are optimized for modern GPUs while maintaining compatibility
- Effects automatically adjust quality based on performance capabilities

## Requirements

- Modern web browser with WebGL support
- JavaScript enabled
- Audio playback capability
- GPU with shader support

## Credits

Created by hot dog studios. 

Some music by Lemmino.   

## License

All rights reserved. (c) hot dog studios 