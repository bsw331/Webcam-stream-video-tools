# Webcam Stream Viewer

A lightweight single-file web page for previewing a live video stream from a network camera or other HTTP-based stream endpoint.

## Features

- Load stream URL directly in the browser
- Support common IP camera / MJPEG / stream endpoints such as `http://192.168.1.4/stream`
- Rotate video: left / right 90 degrees
- Mirror effect
- Vertical flip
- Bilingual UI (Chinese / English)
- No build tool required; just open the HTML file in a browser

## Files

- `webcam-viewer.html` — main application
- `README.md` — English documentation
- `README-zh-CN.md` — Chinese documentation
- `LICENSE` — MIT license

## Quick Start

1. Open `webcam-viewer.html` in a browser.
2. Enter the stream URL, for example:
   - `http://192.168.1.4/stream`
3. Click `Load Stream`.
4. Use the controls to rotate, mirror, or flip the image.

## Notes

- This project is intended for browser-accessible stream endpoints.
- The stream must be reachable from the browser environment.
- If the stream is not directly playable by the browser, the app will attempt an embedded preview fallback.
- Some devices or endpoints may require CORS, network permissions, or special browser support.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Disclaimer

This software is provided for local preview and testing. It does not guarantee compatibility with every camera brand or stream protocol.
