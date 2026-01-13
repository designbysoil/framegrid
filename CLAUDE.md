# FrameGrid

Client-side video contact sheet generator. Single HTML file, no build tools.

## Tech Stack
- React 18 via CDN (unpkg)
- Tailwind CSS via CDN
- Babel standalone for JSX
- HTML5 Video + Canvas API for frame extraction (no FFmpeg/WASM)

## Design System (QF)
- Sidra Green: #11362A (primary), #0B241C (dark)
- Sage: #889A68 (accent), #F4F6F0 (light)
- Neutrals: #E8E8E5, #F5F5F3, #737370

## Key Features
- Drag-and-drop video upload (MP4, MOV, WebM)
- Configurable grid (rows × cols)
- Optional timestamps below each frame
- Resolution presets (target canvas widths):
  - Low: 1200px (default)
  - Medium: 2400px
  - High: 3600px
- Export as PNG/JPG
- Copy to clipboard

## Contact Sheet Styling
- White background
- 40px outer padding
- 20px column gap
- 40px row gap for timestamps (when enabled)
- 18px dark grey (#4A4A4A) timestamp text
- 12px padding between frame and timestamp

## Deployment
- GitHub repo: https://github.com/designbysoil/framegrid
- Hosted on Netlify (auto-deploys from main branch)
- No special headers required (pure client-side)

## Files
- `index.html` - Main application (single file)
- `_headers` - Netlify security headers
- `design-system.html` - QF design system reference (not committed)
