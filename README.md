# SHADOWEED - Synaesthetic Shooter

A unique geometric shooter game that combines fast-paced action with emotional growth mechanics. Every hit you take makes your garden stronger, but each flower remembers your trauma.

## Description

SHADOWEED is a synaesthetic experience where visual and audio elements respond to your gameplay rhythm. The game features a unique mechanic where taking damage grows your garden, creating a visual representation of your journey through trauma and healing.

## Features

- **Geometric Visual Design**: All game elements are rendered using geometric shapes with a cyberpunk aesthetic
- **Dynamic Audio System**: Music and sound effects respond to gameplay intensity and grief levels
- **Growth Mechanics**: Each hit you take grows a flower in your garden that remembers the trauma
- **Rhythm-Based Visuals**: Visual intensity responds to your keypress rhythm
- **Particle Effects**: Dynamic particle system for explosions and damage effects
- **Progressive Difficulty**: Enemy spawn rate increases as you progress

## How to Play

### Controls

- **Movement**: Arrow Keys or WASD
- **Shoot**: Spacebar
- **Toggle Audio**: Click the AUDIO ON/OFF button in the audio panel

### Gameplay

1. Navigate your geometric ship through waves of enemies
2. Shoot enemies to earn points
3. When hit by enemies, flowers grow in your garden
4. Each flower remembers the trauma of the hit that created it
5. The audio intensity increases with your grief level
6. Survive as long as possible while your garden grows

### Game Mechanics

- **Health**: You start with 100% health. Each hit reduces your health.
- **Score**: Earn 10 points for each enemy destroyed.
- **Flowers**: Each hit you take grows a flower in your garden.
- **Grief Level**: Increases with each hit, affecting audio intensity.
- **Visual Intensity**: Responds to your keypress rhythm, creating dynamic visual effects.

## Technical Details

### Built With

- React 18
- HTML5 Canvas
- Tone.js (for audio synthesis)
- Babel Standalone (for JSX transformation)

### Audio System

The game features a dynamic audio system that includes:
- Ambient pad with chord progressions
- MembraneSynth for drone effects
- PolySynth for sound effects
- Reverb, delay, and filter effects that respond to grief levels

### Visual System

- Custom geometric rendering for all game elements
- Particle system with different shape types (triangle, square, hexagon)
- Dynamic grid background that responds to gameplay
- Rhythm-based visual intensity effects

## Installation

To run the game locally:

1. Clone this repository
2. Open `index.html` in a modern web browser
3. Click "INITIALIZE SYSTEM" to start the game

## Browser Compatibility

The game requires a modern browser with support for:
- ES6 JavaScript features
- HTML5 Canvas
- Web Audio API

Tested on:
- Chrome 90+
- Firefox 88+
- Safari 14+

## Development

If you want to modify or extend the game:

1. The game is built as a single React component in `index.html`
2. All game logic is contained within the `ShadoweedGame` component
3. The rendering system uses HTML5 Canvas with custom drawing functions
4. Audio is handled using Tone.js

### Key Components

- `gameStateRef.current`: Contains all game state variables
- `updateGame()`: Main game loop for updating game state
- `renderGame()`: Renders all game elements to canvas
- `checkCollisions()`: Handles collision detection between game objects

## License

This project is open source and available under the MIT License.

## Credits

Created as an experimental synaesthetic game experience.
