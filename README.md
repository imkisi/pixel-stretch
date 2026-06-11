# Pixel Stretch

An experimental interactive, browser-based creative coding project that transforms live webcam feeds into abstract glitch art using HTML5 Canvas and the MediaDevices API.

Instead of a standard video stream, Pixel Stretch slices random vertical fragments of time and stretches them across the viewport, creating shifting, frozen structural layers over reality.

## Features

- **Real-time Fragment Layering:** Non-uniform time slices freeze and overlap dynamically.
- **Pure JavaScript:** Zero external dependencies—built entirely on HTML5 Canvas.
- **Mobile Friendly:** Fully responsive aspect ratios built for mobile browsers and desktop environments alike.
- **Hardware Agnostic:** Automatically adapts to available camera aspect ratios without stretching the raw feed.

## Live Demo

👉 [Insert your GitHub Pages link here]

## Installation & Local Usage

Because the project utilizes webcam streams via `getUserMedia`, modern browsers require a secure context (HTTPS) or a local server context (`localhost`).

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/stratacam.git](https://github.com/imkisi/pixel-stretch.git)
   cd pixel-stretch
   ```
