# 🚛 Amanat Transport | Executive Freight & Fleet Logistics Web Platform

[![GitHub main branch](https://img.shields.io/github/actions/workflow/status/nadeem9986/amt/main.yml?branch=main&style=flat-square&label=deploy)](https://github.com/nadeem9986/amt)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg?style=flat-square)](LICENSE.txt)
[![Status: Production](https://img.shields.io/badge/Status-Production_Ready-10B981.svg?style=flat-square)](#)

A state-of-the-art, high-converting enterprise web application for **Amanat Transport** built with 3D WebGL graphics, modern glassmorphism, executive corporate color themes, interactive freight rate estimation, and real-time shipment telematics.

---

## 🌟 Key Features

* **3D WebGL Constellation Canvas**: Powered by Three.js with real-time mouse-following parallax depth and mobile frame-rate optimization.
* **Executive Corporate Aesthetics**: High-contrast Executive Navy (`#0A1128`) and Safety Amber Gold (`#F59E0B`) design system inspired by top global logistics leaders.
* **Dual Theme Engine**: Instant switcher between **Executive Dark Navy** and **Pearl Corporate Light** modes.
* **Live Shipment Telematics Modal**: Interactive waybill search widget with multi-step status visualizer (Pickup $\rightarrow$ Transit Telematics $\rightarrow$ Terminal Delivery).
* **Interactive Freight Quote Estimator**: Live shipping rate calculator based on Distance (KM), Weight (Tons), and Service Tier.
* **Responsive 3D Card Tilt Effects**: Vanilla JS mouse tilt micro-interactions on service cards and fleet imagery.
* **Interactive FAQ Accordion**: Expandable guidance covering insurance, route telemetry, FTL capacities, and dispatch protocols.

---

## 🛠️ Technology Stack

| Layer | Technology |
| :--- | :--- |
| **Frontend Core** | HTML5 (Semantic Schema Markup), Vanilla CSS3 |
| **3D Graphics** | Three.js (WebGL Particle Constellation & Wireframe Nodes) |
| **Typography** | Space Grotesk (Headings), Plus Jakarta Sans (Body), JetBrains Mono |
| **Icons** | Font Awesome 6 Pro / Free CDN |
| **Structured Data** | JSON-LD (`schema.org/LogisticsService`) for SEO Search Snippets |

---

## 📁 Repository Structure

```text
C:\Users\nad\amt/
├── index.html                  # Single-file bundled Web Application (HTML, CSS, JS, Three.js)
├── top_logistics_websites.md   # Architectural reference guide of top revenue-generating logistics sites
├── README.md                   # Complete repository documentation
├── LICENSE.txt                 # Open source license agreement
└── images/                     # Production fleet imagery
    ├── pic01.jpg               # Hero fleet truck showcase
    ├── pic02.jpg               # Operations & dispatch showcase
    ├── pic03.jpg               # Company depot showcase
    ├── bg.jpg                  # Ambient fallback backdrop
    └── overlay.png             # Pattern texture overlay
```

---

## 🚀 Quick Start & Local Setup

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/nadeem9986/amt.git
   cd amt
   ```

2. **Run Locally**:
   Simply open `index.html` in any web browser, or launch with Live Server:
   ```bash
   npx serve .
   ```

---

## 📄 License & Attribution

Distributed under the **MIT License**. Built for **Amanat Transport**.