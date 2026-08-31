# 🧠♥️ Multimodal Biosignal Fusion: ECG + EEG
---

## 📋 Project Overview

This project contains a **professional, interactive web presentation** showcasing a multimodal biosignal fusion project. The website presents ECG and EEG signal integration for health monitoring using modern, semantic HTML5 and advanced CSS3 styling techniques.

---

### 📄 Files
- **`index.html`** (44 KB) - Complete semantic HTML structure with 9 major sections
- **`style.css`** (21 KB) - Advanced CSS styling with animations and responsive design


## 🛠️ HTML & CSS Skills Demonstrated

### 🏗️ **HTML5 Architecture**
- **Semantic Markup:** Strategic use of `<section>`, `<header>`, and `<article>` with a strict `h1-h3` heading hierarchy.
- **Accessibility & Meta:** Configured viewport, charset metadata, and clean DOM organization.
- **Inline SVG Integration:** Animated background waveforms engineered using `<path>` elements and Quadratic Bézier curves (`viewBox` responsive scaling).
- **Structured Data Layouts:** Implementation of icon systems, feature cards, and itemized clinical statistics.

### 🎨 **Advanced CSS3 & Modern Styling**

#### **Color & Theming**
- Centralized CSS Custom Properties (`:root`) for scalable color management.
- Dynamic text gradients using `-webkit-background-clip`.
- Color utility classes (`.cyan-text`, `.purple-text`, etc.) for consistent component variants.

```css
:root {
  --bg-main: #020617;
  --cyan: #22d3ee;
  --purple: #a855f7;
  /* ... custom variables */
}

```

#### **Layout Systems (Grid & Flexbox)**

* **CSS Grid:** Multi-column layouts (3-column features, 2-column aim/dataset grids) with dynamic `grid-template-columns`.
* **Flexbox:** Precision alignment for hero elements, badge components, icons, and card headers.

#### **Fluid Responsiveness**

* **Fluid Typography & Sizing:** Modern layout scaling using `clamp()`, `min()`, and `max()` functions without relying heavily on rigid media queries.
* **Viewport Relative Units:** Use of `vw`/`vh` for proportional section scaling.

#### **Visual Effects & Animations**

* **Keyframe Animations:** Custom `@keyframes` for continuous pulsing effects on biological icons (heart/brain).
* **Glassmorphism:** Styled cards and badges using `backdrop-filter` blur effects.
* **Interactivity:** Micro-interactions via smooth hover transitions (`transform: translateY()`, dynamic border highlights).

---

## 📦 Component Architecture

The CSS is structured around modular, reusable UI components:

* `.feature-card` - Multi-accent feature containers (cyan, purple, blue variants)
* `.dataset-card` - Specialized layouts for signal data display
* `.stat-box` - Highlight cards for high-impact metrics
* `.aim-card` & `.pipeline-layer` - Structured step and architecture visualizers

---

## 📊 Project Statistics

| Metric | Value |
| --- | --- |
| **HTML File Size** | 44 KB |
| **CSS File Size** | 21 KB |
| **Total Sections** | 9 |
| **Reusable Card Components** | 6+ |
| **CSS Variables** | 12 |
| **Color Variants** | 40+ |
| **Keyframe Animations** | 2+ |
| **Responsiveness** | Mobile to 4K Displays |
