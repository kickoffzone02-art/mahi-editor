# Mahi Editor

A starter browser-based video editor prototype inspired by common editing workflows. It is an original project and is not affiliated with CapCut.

## Features in this starter
- Import one local video file
- Preview, seek, play/pause, skip
- Single-track timeline display
- Set trim start/end
- Add a text overlay
- Filters, playback speed, volume
- Basic fade-in/fade-out during export
- Landscape, portrait, or square output canvas
- Export edited preview to WebM using the browser's MediaRecorder

## Run it
### Simplest (no install)
1. Extract `mahi-editor.zip`.
2. Open `index.html` in a recent desktop Chrome or Edge browser.
3. Click **Import media**, choose a video, make edits, then click **Export video**.

If your browser blocks some media APIs when opened as a local file, use a local server:
- Install Node.js, then open a terminal in this folder.
- Run: `npx serve .`
- Open the local URL shown in the terminal.

## Important limitations
This is a functional starter, not a complete CapCut replacement. Export is WebM and happens in real time; MP4/H.264 export, multiple independent tracks, transitions between separate clips, project saving, cloud storage, and AI captions require additional implementation. Browser codec support varies. Large videos may use significant memory and processing power. The editor does not upload your video to a server.
