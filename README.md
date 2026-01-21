# Berlin Trail Runners - Photo Watermarking Tool

A simple, browser-based web application for watermarking event photos with the Berlin Trail Runners logo and event details.

## Features

- Upload any photo (any size or aspect ratio)
- Automatically crops to 1000x1000px square format
- Adds club logo in upper right corner
- Adds semi-transparent text watermark at bottom with:
  - Event name (customizable)
  - Event date/time (customizable)
- Download watermarked image as JPEG

## Usage

1. Open the tool in your web browser
2. Click "Choose Photo" to select an image
3. Enter the event name (e.g., "Grunewald Social Trail Run")
4. Enter the event date/time (e.g., "Saturday, January 25, 2026 at 9:00 AM")
5. Preview the watermarked image
6. Click "Download Watermarked Photo" to save

## Technical Details

- **Single HTML file** - No dependencies, runs entirely in the browser
- **Image processing** - Uses HTML5 Canvas API
- **Output format** - 1000x1000px JPEG (quality 0.9)
- **Mobile friendly** - Responsive design works on all devices

## Deployment

This tool is hosted on GitHub Pages and can be accessed at:
[https://[your-username].github.io/watermark-tool/](https://[your-username].github.io/watermark-tool/)

## Privacy

All image processing happens in your browser. No data is sent to any server or stored anywhere.

## License

© 2026 Berlin Trail Runners
