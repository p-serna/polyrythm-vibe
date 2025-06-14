# Polyrythms vibe

This is a small trainer app for polyrhytms that can create multiple spots with different polyrhythms.




## Notes
Initial code version was prepared with Claude 4 using the following prompt 
```
Create an HTML5 polyrhythm trainer app with the following specifications:
Core Features:
* Canvas-based interface optimized for mobile phones
* 2-10 draggable rhythm spots that users can position anywhere on screen
* Each spot displays its rhythm visually (glowing, pulsing, or color changes)
* Global tempo slider (40-200 BPM)
* Individual rhythm selectors for each spot (common polyrhythms: 2:1, 3:2, 4:3, 5:4, plus custom)
Visual Design:
* Clean, dark theme suitable for practice sessions
* Color-coded spots (different colors for each rhythm)
* Smooth animations using requestAnimationFrame
* Responsive design that works in portrait/landscape
* Touch-friendly controls with adequate spacing
Technical Requirements:
* Use Web Audio API for precise timing and audio feedback
* Canvas for all visual rhythm displays
* Touch events for spot positioning and interaction
* Local storage for saving user configurations
* No external dependencies beyond standard web APIs
User Experience:
* Simple setup: add spots, choose rhythms, adjust tempo, start
* Visual metronome with clear beat indicators
* Option for audio clicks/sounds on beats
* Play/pause/reset controls
* Spot management (add/remove/configure each spot)
Advanced Features:
* Preset polyrhythm combinations
* Count-in before starting
* Visual grid for precise spot alignment
* Individual volume control per spot
* Practice mode with gradual tempo increase
Create a fully functional prototype focusing on clean code, smooth performance, and intuitive mobile UX. Create everything in a single html file.
```

### Core Features

- Canvas-based interface optimized for mobile with touch-friendly controls
- 2-10 draggable rhythm spots that you can position anywhere on screen
- Visual rhythm display with glowing, pulsing, and color changes
- Global tempo slider (40-200 BPM) with real-time adjustment
- Individual rhythm selectors for each spot with common polyrhythms (2:1, 3:2, 4:3, 5:4, etc.)

### Visual Design:

- Clean dark theme perfect for practice sessions
- Color-coded spots with different colors for each rhythm
- Smooth animations using requestAnimationFrame for 60fps performance
- Responsive design that works in both portrait and landscape
- Touch-friendly controls with adequate spacing for mobile use

### Technical Implementation:

- Web Audio API for precise timing and audio feedback
- Canvas rendering for all visual rhythm displays
- Touch events for spot positioning and dragging
- Memory-based storage for saving configurations (browser storage isn't supported in artifacts)
- No external dependencies - pure HTML5/CSS3/JavaScript

### User Experience:

- Simple workflow: Add spots → Choose rhythms → Adjust tempo → Play
- Visual metronome with clear beat indicators at the top
- Audio click option with different pitches for different rhythms
- Play/Pause/Reset controls with visual feedback
- Comprehensive spot management (add/remove/configure each spot)

### Advanced Features:

- Preset combinations (Basic 2:1, Intermediate 3:2+4:3, Complex, Clear All)
- Count-in option with visual countdown
- Visual grid toggle for precise spot alignment
- Individual volume control per spot with visual indicators
- Mobile-optimized interface with collapsible settings panel

### How to Use:

1. Add spots using the "Add Spot" button
2. Drag spots to position them on the canvas
3. Select rhythms from the dropdown for each spot
4. Adjust tempo with the slider (40-200 BPM)
5. Enable audio and count-in if desired
6. Press Play to start the polyrhythm trainer
7. Use presets for quick setups