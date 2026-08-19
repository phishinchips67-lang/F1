# 🏎️ F1 2026 Power Unit — Interactive Technical Explainer

> *"One crankshaft. Two power sources. 1,000 horsepower. Here's exactly what happens every time Lewis Hamilton touches the throttle."*

![F1 2026 Power Unit](https://img.shields.io/badge/F1-2026-red?style=for-the-badge&logo=formula1)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## 🏁 Overview

This is a **hobby project** I built to understand and visualize the complex world of Formula 1 power unit technology for the 2026 season. It breaks down the Ferrari SF-26 hybrid powertrain into an interactive, visually engaging experience that anyone can explore — whether you're a seasoned F1 fan or just getting into the sport.

**Live Demo:**
https://phishinchips67-lang.github.io/F1/
https://phishinchips67-lang.github.io/F1/index.html

---

### Interactive Power Unit Schematic
Hover over each component (ICE, Turbocharger, MGU-K, Battery, Control Electronics) to see what it does and how it contributes to the overall system.

### Live Lap Simulator
Step through a real racing lap and watch:
- ICE and MGU-K power delivery in real-time
- Battery state of charge fluctuations
- Energy recovery during braking
- The combined 750kW peak power being deployed

### Energy Flow Diagram
Toggle between **Deploying** and **Recovering** modes to understand:
- How energy moves through the system
- The 350kW bi-directional capability of the MGU-K
- The 4MJ battery delta limit per lap

### MGU-K Physics Deep Dive
Explore the Permanent Magnet Synchronous Machine (PMSM) with:
- Animated rotor visualization
- Motor vs. Generator mode comparison
- Field Oriented Control (FOC) explanation with nested loops (ms → µs → ns)

### Circuit Strategy Visualization
See how different tracks affect energy recovery:
- Monaco: 9 MJ per lap (heavy braking)
- Monza: 5 MJ per lap (flat-out)
- 4MJ delta threshold line for battery management

---

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, animations, responsive grid
- **JavaScript** — Interactive simulations, DOM manipulation
- **Google Fonts** — Barlow + Share Tech Mono for that technical F1 feel

---

## Why I Built This

The 2026 F1 regulations introduce significant changes to the power unit architecture. I wanted to:
- **Learn** how hybrid powertrains actually work
- **Visualize** the energy flow that's usually invisible to viewers
- **Share** this knowledge in a way that's accessible and engaging

This isn't just a static page — it's a playground for understanding one of the most advanced powertrains in motorsport.

---

## What You'll Learn

- How the ICE and MGU-K work together (not separately!)
- Why the MGU-K is **never idle** during a lap
- The difference between deploying (350kW) and recovering (350kW)
- What the 4MJ battery delta rule means in practice
- Why Monza is an "energy desert" and Monaco is "energy rich"
- How Field Oriented Control works in a racing context

---

