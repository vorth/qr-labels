# QR Labels Web App

This web app generates a printable grid of 130 labels, each with a unique 2-character code and a QR code encoding the same code.  It was generated from a single prompt to Copilot using GPT-4.1.
The first character is one of: `A`, `B`, `C`, `D`, or space.  
The second character is any uppercase letter `A-Z`.

This app was vibe-coded with GitHub Copilot using GPT 4.1.  I've captured some potential improvements as issues.

## Features

- **Print-friendly layout:** Click "Print Labels" to print the grid.
- **Adjustable columns:** Set the number of columns for the grid.
- **Export CSV:** Download a CSV file of all codes.
- **QR codes:** Each label displays a QR code for its code.

## Usage

1. Open `index.html` in your browser.
2. Use the controls to print or export codes.
3. Adjust the number of columns for your preferred layout.

## Dependencies

- [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) (loaded via CDN)

## Customization

- To change the number of labels, edit the code in `index.html` where `labelCodes` is defined.
- To change label size or style, edit the CSS in `index.html`.

##
