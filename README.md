# MAXCHICHAR LIVE RECEIPT

Turn static receipts into a premium, interactive presentation layer people can actually read and explore.

## Overview

MAXCHICHAR LIVE RECEIPT is a web application that transforms ordinary receipts and proof-of-payment artifacts into polished, physics-driven interactive surfaces. Instead of showing flat, disposable screenshots, receipts become readable hero objects with motion, depth, and interaction.

This application solves a common product problem: receipts and proof-of-payment artifacts usually feel disposable, unreadable, and visually weak. It provides a stronger presentation layer for checkout flows, digital storefronts, dashboards, or proof-of-purchase experiences.

## Features

### 🎯 Core Functionality
- **Physics-Driven 3D Surface**: Custom Verlet cloth system creates realistic cloth physics and movement
- **Interactive Dragging**: Grab and drag the receipt to inspect it from different angles
- **Real-time Rendering**: Canvas triangle mapping for smooth, performant 3D rendering

### 🎨 Visual & UI
- **Readable Output**: Larger, front-facing display that's easy to inspect while maintaining premium physical feel
- **Dark Mode**: Toggle between light and dark themes with smooth transitions
- **Glass Panel UI**: Modern, editorial layout with frosted glass effects
- **Responsive Design**: Works across different screen sizes and devices

### ✏️ Customization
- **Custom Text Editing**: Edit receipt content including:
  - Store name
  - Items and quantities
  - Prices and totals
  - Dates and transaction details
- **Multiple Templates**: Choose from different receipt styles:
  - Default template
  - Minimal template
  - Detailed template
  - Branded template

### 📤 Import & Export
- **User Uploads**: Upload your own receipt image and instantly project it onto the live 3D surface
- **PNG Export**: Download high-quality PNG images of the 3D receipt
- **WebM Export**: Export animated WebM videos for sharing, presentations, or documentation

### 🛠️ Technical Stack
- **Vanilla JavaScript**: No frameworks or dependencies
- **HTML Canvas**: Custom texture generation and rendering
- **Custom Mesh Deformation**: Advanced 3D surface manipulation
- **Browser-Native File Handling**: Efficient upload and processing
- **Physics Engine**: Custom Verlet integration for realistic cloth simulation

## Use Cases

Perfect for:
- **Digital Storefronts**: Premium product presentation and checkout confirmations
- **Payment Flows**: Enhanced proof-of-purchase experiences
- **Dashboards**: Interactive receipt visualization and analytics
- **Demos & Presentations**: High-quality visual content for marketing
- **Documentation**: Professional receipt examples and templates
- **Product Storytelling**: Premium visual narratives for e-commerce

## Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No build process or dependencies required

### Installation

1. Clone the repository:
```bash
git clone https://github.com/maxchichar/MAXCHICHAR-LIVE-RECEIPT.git
```

2. Navigate to the project directory:
```bash
cd MAXCHICHAR-LIVE-RECEIPT
```

3. Open `index.html` in your web browser

That's it! The application runs entirely in the browser with no server setup required.

## Usage

### Basic Interaction
1. **View the Receipt**: The receipt appears as a 3D cloth surface
2. **Drag to Interact**: Click and drag the receipt to move and inspect it
3. **Toggle Dark Mode**: Use the dark mode button for comfortable viewing

### Customizing Receipts
1. **Edit Content**: Click the "Edit Receipt" button to modify:
   - Store name and details
   - Line items and prices
   - Totals and transaction info
2. **Change Templates**: Select different receipt styles from the template options
3. **Upload Your Own**: Click "Upload Receipt" to use your own receipt image

### Exporting
1. **PNG Export**: Click the export button to download a high-quality image
2. **WebM Export**: Export an animated video showing the receipt in motion

## Technical Details

### Physics System
- **Verlet Integration**: Custom cloth physics simulation
- **Gravity & Constraints**: Realistic movement and deformation
- **Mesh Resolution**: 26×52 grid for smooth cloth behavior
- **Camera System**: Adjustable FOV and positioning

### Rendering Pipeline
- **Canvas 2D Context**: Hardware-accelerated rendering
- **Triangle Mapping**: Efficient 3D-to-2D projection
- **Device Pixel Ratio**: Sharp rendering on high-DPI displays
- **Performance Optimized**: 60fps animation loop

### File Handling
- **Image Upload**: Browser-native file API
- **Texture Generation**: Dynamic canvas texture creation
- **Export Formats**: PNG and WebM with quality controls

## Browser Compatibility

- ✅ Chrome/Edge (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Opera

Requires modern JavaScript and Canvas 2D support.

## Performance

- Optimized for 60fps rendering
- Efficient memory usage with canvas-based textures
- Responsive to different screen sizes
- Minimal CPU/GPU overhead

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is open source and available under the MIT License.

## Author

**MAXCHICHAR**
- GitHub: [github.com/maxchichar](https://github.com/maxchichar)
- X/Twitter: [@maxchichar](https://x.com/maxchichar)

## Acknowledgments

Built with vanilla JavaScript, HTML canvas texture generation, custom mesh deformation, browser-native file handling, multiple receipt templates, custom text editing, dark mode support, and high-quality PNG and animated WebM export functionality.

---

**MAXCHICHAR LIVE RECEIPT** — Transforming static receipts into premium, interactive experiences.