# Project 1: Static Webpage Design
### Foundations of Visual Architecture & Technical Integrity
**Batch: 2026** | Internal Engineering Track: Phase I

---

## 📋 Project Overview
This repository contains a pixel-perfect, highly structured static webpage built as part of the **DecodeLabs Frontend Development Industrial Training Kit**. 

The core objective of this project is to master **Semantic Integrity** and understand the fundamental relationship between layout content and modular styling rules before transitioning into dynamic, data-driven applications.

---

## 🛠️ Key Requirements & Core Skills
* **Semantic DOM:** Developed using explicit HTML5 landmarks rather than generic container layout structures ("div soup") to guarantee machine readability, SEO optimization, and accessibility (A11Y).
* **Macro Layout:** Structured around a strict 12-column **CSS Grid** architecture with standard dimensions (`max-width: 1200px`, `gutter: 24px`).
* **Micro Component Alignment:** Utilizes 1-Dimensional **Flexbox** implementations for navigation, layout modules, and internal card alignments.
* **Asset Management:** Employs explicit dimensional constraints (`width` and `height` attributes on images) to eliminate layout shifts (CLS prevention).
* **The DRY Principle:** Employs strict **BEM (Block-Element-Modifier)** CSS naming logic to enable reusable, modular components and eliminate redundant styles.

---

## 📂 Project Structure
```text
├── index.html        # Main markup file containing the semantic DOM structure
├── style.css         # External stylesheet utilizing BEM architectural standards
└── README.md         # Project documentation and guidelines