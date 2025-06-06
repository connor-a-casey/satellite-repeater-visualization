# Quantum Repeater Satellite Chain Visualization

<div align="center">
    <img src="assets/visual.gif" alt="Quantum Repeater Visualization Demo">
</div>

## Overview

This project provides an interactive 3D visualization of a quantum repeater satellite chain between Boston and Perth. The visualization can be edited to reflect your specific experimental setup regarding quantum satellite communications. 

## Features

- Interactive 3D visualization of Earth with realistic textures
- Dynamic satellite chain placement between Boston and Perth
- Adjustable number of quantum repeaters (1-50)
- Realistic orbital mechanics and great circle calculations
- Immersive space environment with starfield background
- Smooth camera controls with auto-rotation

## Technologies Used

- Three.js for 3D rendering
- HTML5/CSS3 for UI components
- JavaScript for interactive features
- WebGL for hardware-accelerated graphics

## Getting Started

### Prerequisites

- A modern web browser with WebGL support
- Visual Studio Code (recommended)
- VS Code Live Server extension

### Browser Compatibility

The visualization works best in modern browsers that support WebGL:
- Chrome (recommended)
- Firefox
- Safari
- Edge

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/connor-a-casey/satellite-repeater-benchmark
   ```

2. Install VS Code Live Server:
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X on Mac)
   - Search for "Live Server"
   - Install the extension by Ritwick Dey

### Running the Project

#### Method 1: Using VS Code Live Server (Recommended)
1. Open the project folder in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. The visualization will automatically open in your default browser

#### Method 2: Direct Browser Opening
1. Navigate to the project directory
2. Open `index.html` in your web browser

### Usage

1. Use the slider to adjust the number of quantum repeaters in the chain

2. Interact with the visualization:
   - Click and drag to rotate the view
   - The visualization will auto-rotate
   - Zoom controls are disabled to maintain optimal viewing distance

## Technical Details

The visualization implements:
- Great circle calculations for optimal satellite placement
- Realistic Earth rendering with normal mapping and specular highlights
- Dynamic satellite chain generation with proper spacing
- Efficient WebGL rendering with Three.js

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Three.js community for the 3D library that was used