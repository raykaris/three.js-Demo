# three.js-Demo

A simple demo project using [three.js](https://threejs.org/) to render a 3D scene in the browser.  
Includes both a minimal HTML+JS setup and a modern [Vite](https://vitejs.dev/) + ES modules workflow.

## Features

- Minimal setup with three.js via CDN (basic)
- Modern development with Vite (Vite)
- Example of a basic 3D scene with a dodecahedron and a box
- OrbitControls for interactive camera movement
- Animation loop

## Getting Started
1. clone the repository:
```sh
git clone https://github.com/your-username/three.js-Demo.git
cd three.js-Demo/basic
```

2. Open index.html in your browser:

   You can simply open the index.html file in your browser.
   For best results, use a local server (e.g., with Python):
   ```sh
   python3 -m http.server
   ```

### 1. Basic HTML Demo

1. Open index.html in your browser  
   _or_  
   Start a local server in the project root:
   ```sh
   python3 -m http.server
   ```
   Then visit [http://localhost:8000/basic/](http://localhost:8000/basic/) in your browser.

### 2. Vite + three.js Demo

1. Go to the Vite project directory:
   ```sh
   cd Vite
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the development server:
   ```sh
   npm run dev
   ```
   Then open the local URL shown in your terminal (usually [http://localhost:5173/](http://localhost:5173/)).

## File Structure

```
basic/
  ├── index.html   # Minimal HTML demo with import maps
  └── main.js      # Main JavaScript for basic demo

Vite/
  ├── index.html   # Vite entry HTML
  └── src/
      └── main.js  # Main JavaScript for Vite demo
  └── package.json # Vite config and dependencies
```

## Requirements

- Modern web browser with ES module support
- [Node.js](https://nodejs.org/) (for Vite demo)

