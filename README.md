# qr-code-generator
Local QR Code Generator

This repo will allow you to launch a basic QR code generator. It requires basic familiarity with editing HTML files. This can be done with any text editor.

## Editing

Open the `index.html` file in a text editor. Scroll until the Javascript is visible with the "pattern" and "stores". The pattern is the base url for the QR Code. The stores are store id's that are appended to the base url. Add store id's as necessary - these are in array format.

## Launch

Open the `index.html` file in Chrome. The QR Codes should generate and resolve to the "pattern" + "store" for each store in the array.