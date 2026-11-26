# ClipX Studio

Mobile-friendly browser video editor prototype. Media stays in your browser.

## Features
- Import video, preview and timeline seek
- Trim start/end, playback speed, volume
- Aspect presets (9:16, 16:9, 1:1)
- Filters and center text overlay
- Import/play a separate audio track (preview)

## Export
Captures the video preview as WebM in browsers supporting MediaRecorder/captureStream. Browser/device support varies. Separate music currently previews but is not mixed into the export.

## Deploy
In repository Settings → Pages, set Build and deployment → Source to GitHub Actions. Workflow deploys on pushes to main.
