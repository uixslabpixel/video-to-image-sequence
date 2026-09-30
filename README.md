# Video to Image Sequence

Browser tool that turns a video into a per-frame `.webp` image sequence, for scroll-driven canvas animations and similar image-sequence techniques. Everything runs locally in the browser; the video is never uploaded.

## Features

- Adjustable compression intensity (0–100) with presets
- Before/after quality comparison with 100% and 200% zoom, plus four compression levels side by side
- Output frame rate (auto-detects the source fps), output width, and in/out range
- Custom file prefix and start number (`frame_0001.webp`, …)
- Size estimate per frame and for the whole sequence
- Sequence player to check the result, then download everything as a ZIP
- Ready-to-copy scroll-driven canvas snippet

## Usage

Open `index.html` in Chrome, Edge, or Firefox (Safari cannot encode WebP from canvas), or serve the folder:

```bash
python3 -m http.server 5173
```

## Credits

Created by [vickyfikri](https://github.com/vickyfikri90-cloud).

UI follows the Experiment Tool kit design system.
