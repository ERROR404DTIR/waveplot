# Waveplot

A private, browser-only audio waveform viewer. Drop in a local audio file, inspect its waveform, and export a lightweight SVG.

<p align="center"><svg width="100%" viewBox="0 0 720 160" xmlns="http://www.w3.org/2000/svg"><rect width="720" height="160" rx="16" fill="#0b1020"/><path d="M24 80H696" stroke="#293854" stroke-width="1"/><path d="M24 80 Q38 80 45 45 T65 80 T85 110 T105 80 T125 30 T145 80 T165 125 T185 80 T205 55 T225 80 T245 100 T265 80 T285 20 T305 80 T325 130 T345 80 T365 50 T385 80 T405 115 T425 80 T445 35 T465 80 T485 105 T505 80 T525 25 T545 80 T565 120 T585 80 T605 55 T625 80 T645 100 T665 80 T696 80" fill="none" stroke="#62e3c1" stroke-width="2"><animate attributeName="stroke-dasharray" values="0 1500;1500 0" dur="4s" repeatCount="indefinite"/></path><text x="24" y="145" fill="#91a0ba" font-family="monospace" font-size="10" letter-spacing="3">LOCAL AUDIO · VISUAL WAVEFORM · SVG EXPORT</text></svg></p>

## Features
- Open audio files from your device using drag and drop or the file picker.
- Decode audio locally with the browser's Web Audio API.
- View a compact waveform and inspect duration, channels, and sample rate.
- Play the selected audio in the browser.
- Export the waveform as a standalone SVG.
- No upload, account, server, or third-party library.

## Run
Open `index.html` in a modern browser. No installation or build step is required.

## Compatibility
Audio decoding depends on formats supported by the browser. Large files may use substantial memory.

## Privacy
The selected file is processed locally in the page. Waveplot does not transmit audio data.

## License
MIT
