# Chrome Extension Starter Template

This is a starter template for building a Chrome extension using Manifest V3.

## File Structure

- `manifest.json`: The main configuration file for the extension.
- `popup.html`: The HTML file for the extension's popup.
- `popup.js`: The JavaScript file for the popup's logic.
- `popup.css`: The CSS file for styling the popup.
- `content.js`: A content script that gets injected into web pages.
- `background.js`: The service worker for handling background tasks.
- `images/`: A directory for icons.

## How to Use

1.  Clone or download this repository.
2.  Open Chrome and navigate to `chrome://extensions`.
3.  Enable "Developer mode" in the top right corner.
4.  Click "Load unpacked" and select the directory containing this template.
5.  The extension should now be loaded and active.

## Placeholder Icons

The icons in the `images/` directory are placeholders. You should replace them with your own icons. The required sizes are:
- `icon16.png` (16x16)
- `icon48.png` (48x48)
- `icon128.png` (128x128)