# MAXCHICHAR LIVE RECEIPT

**Turn any receipt into a living, interactive 3D cloth simulation.**

An immersive single-file web demo where a receipt becomes a physically simulated, draggable digital sheet with realistic cloth physics, real-time texture mapping, and smooth interactions.

---

## What It Is

**MAXCHICHAR LIVE RECEIPT** is a creative coding project that transforms a static receipt into a dynamic, deformable 3D object. 

Using a custom **Verlet-based cloth physics** system, the receipt behaves like flexible paper or fabric you can grab, drag, swing, and disturb it, watching it ripple and settle with natural inertia and gravity.

It includes:
- Real-time texture mapping of your uploaded receipt image onto the 3D mesh
- A synchronized flat preview that always keeps the content readable
- Subtle camera movement based on your pointer
- Beautiful visual effects (floating motes, glows, shadows, and paper-like back texture)

Everything runs in a single `index.html` file with **zero dependencies** — pure vanilla HTML, CSS, and JavaScript.

## Key Features

- **Verlet Cloth Physics**: 26×52 particle grid with structural, shear, and bend constraints
- **Interactive Dragging**: Click and drag any part of the receipt to manipulate it in real time
- **Pointer-Controlled Camera**: Subtle 3D perspective shifts as you move your mouse/touch
- **Image Upload**: Drag & drop or upload your own receipt image instantly
- **Procedural Default Receipt**: Beautiful mock receipt for "THE FLORNRM SHOP" with tech-themed items
- **Live Flat Preview**: Always-visible clean version of the receipt below the simulation
- **Visual Polish**: Floating golden motes, pulse effects, soft shadows, and glassmorphic UI

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/maxchichar/MAXCHICHAR-LIVE-RECEIPT.git

2. Open index.html in any modern browser (Chrome, Firefox, Edge, Safari).
3. Interact:
  * Click and drag the receipt to feel the physics
  * Move your mouse around for camera tilt
  * Use the upload button to replace the receipt with your own image

## TechnologiesHTML5 Canvas for both the 3D scene and preview

* Vanilla JavaScript: custom Verlet integration, texture mapping, and pointer handling
* CSS: modern glassmorphism design and responsive layout

No frameworks. No external libraries.

## Project Structure
```
MAXCHICHAR-LIVE-RECEIPT/
├── index.html          # Entire application (single file)
├── LICENSE
└── README.md
```
## 🤝 Contributing

Contributions are welcome and greatly appreciated! Whether it's fixing a bug, improving the physics, adding new features, enhancing the UI, or suggesting ideas and every contribution helps make this project better.

### How to Contribute

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-idea`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-idea`)
5. Open a Pull Request

**Thank you to all the wonderful people who have contributed to this project!** 💛

Your name could be here next! 

## Concept
This project explores turning everyday digital artifacts (like receipts) into living, interactive objects. It combines physics simulation, creative rendering, and delightful interactions into one engaging experience.Perfect for portfolios, creative coding showcases, or experimental web interfaces.

Made with ❤️ by maxchichar
Chibueze Charles Maxwell
