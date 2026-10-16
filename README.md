# 🛠️ Forge3D Studio

**Forge3D Studio** is a browser-based, zero-dependency 3D printing suite combining a **Multi-Object Parametric CAD Modeler**, **Interactive Layer Slicer & G-Code Generator**, and **Direct 3D Printer Control Hub** (via WebSerial USB & Moonraker/OctoPrint REST APIs) in a single HTML file.

![Three.js](https://img.shields.io/badge/Three.js-r128-black?style=flat-square&logo=three.js)
![WebSerial](https://img.shields.io/badge/API-WebSerial%20USB-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ✨ Core Features

### 1. Parametric 3D CAD Generators (`Design & Layout`)
- **Lampshade Modeler**: Procedural ribs, vertical wave frequencies, helical twist, internal warm filament bulb simulation, and integrated socket mounts (**E27**, **E14**, **US Uno**, **Harp Finial**, or Custom).
- **Planters & Vases**: Customizable flare profiles, ribs, and automatic watertight bottom drainage channels.
- **Involute Spur Gears**: Parametric tooth count, module (`mm`), pressure angle, thickness, center bore, and keyway.
- **Grid Storage Organizers**: Custom compartment rows/columns, wall thickness, corner fillets, and stackable rims.
- **Desk Cable Clips & Custom Primitives**: Parametric desk clamp channels plus standard primitives (*Cylinder, Cube, Torus, Cone, Sphere*).
- **External `.STL` Importer & Auto-Nesting**: Import binary or ASCII `.stl` meshes onto the build plate and auto-pack multiple objects with safety margins.

### 2. Built-In Slicer & Toolpath Preview (`Preview & Slice`)
- **Real-Time Layer Slicing**: Adjustable layer height (`0.12mm – 0.28mm`), wall loops, rectilinear infill percentage, spiral vase mode, and print speeds.
- **Interactive 3D Layer Scrubber**: Scrub through individual Z-layers or animate the virtual nozzle tracing perimeters and infill paths.
- **Direct Export**: Export single or merged multi-object **Binary `.STL`** meshes (`Z-up`, millimeter-scaled) or downloadable **Marlin/Klipper `.GCODE`**.

### 3. Direct 3D Printer Control Hub (`Printer Control`)
- **USB WebSerial (`navigator.serial`)**: Connect directly to Marlin, Klipper, or RepRap boards over USB (`115200` / `250000` baud) with live G-code streaming.
- **Wireless REST API**: Send jobs and commands to **Moonraker / Klipper / OctoPrint** instances over local Wi-Fi.
- **3D Digital Twin Simulator**: Test `G28` homing, X/Y/Z axis jogging, PID heater curves, and live G-code execution on an interactive virtual printer before running hardware jobs.

---

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone [https://github.com/eemir2603/Forge3D-Studio.git](https://github.com/eemir2603/Forge3D-Studio.git)
   cd Forge3D-Studio
