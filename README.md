# STRIDE | Timeless Velocity

![Project Status](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![Tech](https://img.shields.io/badge/Built%20With-HTML%20%7C%20Tailwind%20%7C%20JS-black?style=for-the-badge)

<div align="center">
  <br />
  <a href="https://stridecars.vercel.app/"><strong>➥LIVE DEMO</strong></a>
  <br />
  <br />
  <img src="./hero.png" alt="Stride Project Preview" width="100%" style="border-radius: 10px; border: 1px solid #333;">
</div>

<br />

## About The Project

**Stride** is an immersive, high-fidelity digital museum and marketplace dedicated to the world's most definitive automotive engineering feats. 

Designed with a **"Quiet Luxury"** aesthetic, the platform bridges the gap between 90s analog legends (like the McLaren F1) and modern engineering marvels (like the Bugatti Chiron). The interface prioritizes cinematic visuals, smooth micro-interactions, and a sophisticated dark-mode palette to let the machinery take center stage.

### Key Features

* **Cinematic Hero Section:** Features a seamless, high-quality video loop background with a gradient overlay for immersive storytelling.
* **Glassmorphism UI:** Frosted glass navigation, cards, and overlays using `backdrop-filter` for a premium, layered feel.
* **Masonry Gallery Grid:** A responsive, asymmetrical grid layout that showcases vehicle photography dynamically.
* **Micro-Interactions:** Smooth CSS hover states, scaling effects, and gold accent reveals (`#eec02b`) upon interaction.
* **Dynamic Engineering Archive:** A horizontal scroll section highlighting technical details (Engines, Carbon Fiber, Aero).
* **Auto-Updating Footer:** JavaScript implementation to ensure the copyright year is always current.

---

## Tech Stack

This project was built using a modern, utility-first approach to ensure performance and maintainability.

| Technology | Usage |
| :--- | :--- |
| **HTML5** | Semantic structure and SEO optimization. |
| **Tailwind CSS** | Styling, responsive design, and custom configuration for the "Luxury" theme. |
| **JavaScript (ES6+)** | DOM manipulation for the hero slider and dynamic date handling. |
| **Google Fonts** | *Manrope* (UI) and *Playfair Display* (Headings) for typographic hierarchy. |
| **Material Symbols** | Ligature-based iconography for a clean, vector-sharp look. |

---

## Design Philosophy

The design language of Stride is built on three pillars:

1.  **Dark Mode First:** Using `bg-matte-black` (`#0a0a0a`) and `bg-background-dark` (`#121212`) to create depth and allow the car photography to pop.
2.  **Gold & Platinum:** A restrained color palette. Primary actions use Muted Gold (`#eec02b`), while secondary text uses Platinum (`#d1d5db`).
3.  **Depth & Texture:** Extensive use of `bg-white/5` and `border-white/10` to create subtle boundaries without harsh lines.

---

## Getting Started

To run this project locally, follow these steps:

### Prerequisites

* A modern web browser (Chrome, Firefox, Safari).
* A code editor (VS Code recommended).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/gideonabe/stridecars.git](https://github.com/gideonabe/stridecars.git)
    ```

2.  **Navigate to the project directory:**
    ```bash
    cd stride
    ```

3.  **Run the project:**
    * Since this project uses the Tailwind CDN for rapid prototyping, you can simply open `index.html` in your browser.
    * *Recommended:* Use the "Live Server" extension in VS Code for real-time updates.

---

## Project Structure

```text
stridecars/
├── assets/
│   ├── images/          # Car photography
│   └── videos/          # Hero loop video
├── index.html           # Main landing page
├── mclaren.html         # Detail page: McLaren F1
├── bugatti.html         # Detail page: Bugatti Chiron
├── dodge.html           # Detail page: Dodge Charger
├── ferrari.html         # Detail page: Ferrari F50
└── README.md            # Documentation
``` 
## License
Distributed under the MIT License. See LICENSE for more information.


