# 📊 Graph Studio

> A minimalist, mobile-first interactive graph visualizer — built with vanilla HTML, CSS & Three.js.

**🔗 Live Demo → [graph-studio-visualize-mobile.onrender.com](https://graph-studio-visualize-mobile.onrender.com)**

Made by **Amlan Dey**

---

## ✨ Features

### 📈 2D Graphing
- Input X & Y coordinates for each data point
- Renders a smooth gradient line chart with glowing data points
- Area fill under the curve with animated glow effect
- Labeled axes with auto-scaled tick marks
- Touch a data point on mobile (or hover on desktop) to see a coordinate tooltip

### 🧊 3D Graphing
- Input X, Y & Z coordinates for each data point
- Interactive 3D scatter plot powered by **Three.js**
- Color-coded XYZ axes with floating axis labels
- Drop lines from each point down to the grid for depth clarity
- Points connected by a glowing line
- Smooth **auto-rotation** when idle

### 📱 Mobile-First Design
- Native **bottom sheet** UI for entering data points — swipe down to dismiss
- **Bottom tab bar** — thumb-friendly navigation (Points / Plot / Clear / Switch Mode)
- **Floating action buttons** always visible on the canvas
- 1-finger drag → rotate 3D scene
- 2-finger pinch → zoom in/out on 3D
- Touch a 2D point → tooltip pops up and auto-hides
- `inputmode="decimal"` on inputs for the right mobile keyboard
- Safe area insets respected for notched iPhones
- No page zoom, no horizontal scroll

### 🎨 Design
- Dark oscilloscope-inspired aesthetic
- Dot-grid background texture
- Neon cyan / red / lime accent system
- `Space Mono` + `Syne` font pairing
- Smooth sheet animations with cubic-bezier easing
- Color-coded points with glow shadows

----

## 🎮 How to Use

### Adding Points
1. Tap **POINTS** in the bottom tab bar (or the ➕ FAB button)
2. The data entry sheet slides up from the bottom
3. Tap **ADD** to add a new point row
4. Enter your **X** and **Y** values (and **Z** if in 3D mode)
5. Repeat for as many points as you need

### Switching Modes
- Tap **SWITCH** in the tab bar to toggle between **2D** and **3D** mode
- Or use the **2D / 3D** pill in the top bar

### Plotting
- Tap **PLOT** in the tab bar or the chart FAB button
- The graph renders instantly on the canvas

### 3D Navigation (3D Mode)
| Gesture | Action |
|--------|--------|
| 1-finger drag | Rotate the scene |
| 2-finger pinch | Zoom in / out |
| Mouse drag | Rotate |
| Scroll wheel | Zoom |
| Idle | Auto-rotates gently |

### Clearing
- Tap **CLEAR** in the tab bar or inside the sheet to remove all points and reset the canvas

---

## 🏗️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| HTML5 Canvas API | 2D graph rendering |
| [Three.js r128](https://threejs.org/) | 3D scene, geometry & lighting |
| CSS Custom Properties | Theming & design tokens |
| Vanilla JavaScript | All logic, no frameworks |
| Google Fonts | Space Mono + Syne typefaces |

> **No build tools. No npm. No frameworks.** Just a single self-contained HTML file.

---

## 📁 Project Structure

```
graph-studio/
│
├── graph_studio.html   # The entire app — HTML + CSS + JS in one file
└── README.md           # This file
```

---

## 🌐 Deployment

The app is deployed as a static site on **Render**.

---

## 📸 Screenshots

| 2D Graph | 3D Graph | Data Entry |
|----------|----------|------------|
| Gradient line chart with glowing points | Interactive rotatable 3D scatter plot | Slide-up bottom sheet |

---

## 🙌 Author

**Amlan Dey**

---

  ## 💰 You can help me by Donating
[![Support Me via UPI](https://img.shields.io/badge/Support_Me-UPI-6739B7?style=for-the-badge&logo=phonepe&logoColor=white)](https://support-me-fbhd.onrender.com)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
