# iOS 2.0 IPA Legacy Converter Web App Example

A lightweight, purely client-side web application designed to demonstrate parsing and structural conversion of legacy iOS 2.0 `.ipa` packages into structured zip configurations or metadata representations compatible with modern archival emulation layers.

## Features
- **Client-Side Processing:** No server-side file uploads; execution runs completely within the browser sandbox via standard HTML5 File APIs.
- **Legacy Framework Recognition:** Targets specific structural patterns inherent to early iPhone OS 2.0 application bundles (`Payload/AppName.app/*`).
- **Binary Plist Conversion Placeholder:** Includes hooks for extracting and viewing low-level embedded metadata like `Info.plist`.

## Installation & Usage
1. Download and extract the contents of the ZIP archive.
2. Open `index.html` in any modern web browser (Safari, Chrome, Firefox).
3. Select a legacy iOS 2.0 `.ipa` file to run the conversion simulation.

## License
MIT License. For archival and educational evaluation purposes only.
