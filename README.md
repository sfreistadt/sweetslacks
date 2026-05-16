# Sweet Slacks

A Place That We Call Home

## Structure

The site has been unbundled from a single 4.4MB file into a clean, maintainable structure:

- `index.html` (96KB) - Main HTML file with inline CSS
- `fonts/` (772KB) - Web fonts (WOFF2 format)
- `images/` (2.6MB) - Image assets (JPG, PNG)
- `index_bundled_backup.html` - Original bundled version (backup)

## Responsive Design

The site includes responsive breakpoints for:
- Desktop (default)
- Tablet (768px and below)
- Mobile (480px and below)

The viewport meta tag ensures proper scaling on all devices.

## Development

To view the site locally:
1. Open `index.html` in a web browser
2. Or use a local server: `python3 -m http.server 8000`

## Changes Made

1. Extracted all embedded assets from the bundled HTML
2. Organized assets into separate directories (fonts/, images/)
3. Added comprehensive responsive CSS for mobile devices
4. Reduced main HTML file size from 4.4MB to 96KB
5. Fixed asset references to use relative paths

The unbundled structure makes the site easier to:
- Debug and troubleshoot
- Modify and maintain
- Version control
- Optimize and cache
