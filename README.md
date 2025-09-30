# Hello Extensions

This is a simple browser extension that displays a popup with a greeting message when clicked. I created this extenstion to learn the basics of browser extension development.

## Files

- `manifest.json`: The manifest file that defines the extension's metadata and behavior.
- `hello.html`: The HTML file that contains the content of the popup displayed by the extension.
- `icon.png`: The icon for the extension (not included in this snippet).

## Installation

1. Save the above files in a directory named `hello-extension`.
2. Open your browser's extensions page (e.g., `chrome://extensions/` for Chrome).
3. Enable "Developer mode" (if applicable). The toggle is usually found in the top right corner.
4. Click "Load unpacked" and select the `hello-extension` directory.
5. The extension should now appear in your browser's toolbar. Click the icon to see the popup.

## Usage

Click the extension icon in the browser toolbar to open the popup and see the greeting message "Hello, Extensions!". You should pin the extension to the toolbar for easy access.

## Troubleshooting

If the extension does not appear or function as expected, ensure that:
- The `manifest.json` file is correctly formatted and contains all required fields.
- The `hello.html` file is properly linked in the manifest.
