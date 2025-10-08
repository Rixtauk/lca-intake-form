# LCA Intake Form

A standalone React intake form that runs without a build step, perfect for static hosting.

## Features

- Self-contained React form in a single HTML file
- Loads React, Tailwind CSS, and Babel from CDNs
- Complete validation, paging, and status messaging
- Webhook submission with automatic reset on success
- Inline SVG icons (no external dependencies)

## Usage

1. **Local Development**: Open `index.html` in any modern browser
2. **Local Server**: Run `python3 -m http.server` in this directory
3. **Production**: Deploy to any static hosting service

## Deployment Options

- GitHub Pages (recommended for this repo)
- Netlify Drop
- AWS S3 Static Website
- Vercel
- Any static file hosting service

## Testing

After deployment:
1. Fill out and submit the form
2. Verify your Make webhook receives the payload
3. Confirm the form resets automatically on success

## Live Demo

Once deployed to GitHub Pages, the form will be available at:
`https://rixtauk.github.io/lca-intake-form/`