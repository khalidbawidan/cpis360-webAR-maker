# WebAR Project (Hiro Marker)
**Author:** khalid bawidan

## About This Project
This is a simple Augmented Reality (AR) web application I built using A-Frame and AR.js. When you point your camera at a Hiro marker, the app displays a few 3D shapes (a torus knot, an icosahedron, and a cylinder) hovering over the marker with different animations, along with my name.

## Built With
- **HTML/CSS**: Basic structure and styling.
- **A-Frame**: For rendering the 3D scene and shapes.
- **AR.js**: For tracking the Hiro marker via the webcam.

## Features
- Detects the standard "Hiro" marker and displays 3D objects over it.
- **Torus Knot**: Floats up and down while rotating.
- **Icosahedron**: Pulses in size and rotates.
- **Cylinder**: Bounces and spins.
- **Text**: Displays the name "khalid bawidan" fading in and out.
- Simple lighting setup to make the 3D materials look good.

## How to Run It Locally
Browsers don't allow camera access when you simply double-click an HTML file (`file://` protocol), so you need to run a local server.

1. Download or clone this project folder.
2. Start a local server inside the folder. For example, if you have Python installed, you can run:
   ```bash
   python -m http.server 8000
   ```
   Or if you use Node.js:
   ```bash
   npx serve .
   ```
3. Open your browser and go to `http://localhost:8000`.
4. Allow camera access when the browser asks for permission.
5. Point your camera at a Hiro marker! You can just open the `print-marker.jpg` file in this folder on your phone screen, or print it out on paper.

## Hosting on GitHub Pages
This project is easy to host on GitHub Pages because it gives you the secure HTTPS connection required for camera access.

1. Push this project to a repository on your GitHub account.
2. Go to the repository's **Settings** > **Pages**.
3. Under **Branch**, select `main` (or `master`) and save.
4. Wait a minute or two, and GitHub will provide a live URL.
5. Open that link on your phone or laptop, allow camera permissions, and aim the camera at the `print-marker.jpg` image.
