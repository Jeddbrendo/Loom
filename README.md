<div align="center">

# LOOM Timelines

**A highly-performant, standalone web application for visualizing complex history.**

[![Built with HTML5 Canvas](https://img.shields.io/badge/Built_with-HTML5_Canvas-E34F26?style=flat-square&logo=html5)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Vanilla JS](https://img.shields.io/badge/Logic-Vanilla_JS-F7DF1E?style=flat-square&logo=javascript)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

</div>

---

LOOM Timelines is a powerful, zero-dependency HTML application designed for creating and managing intricate historical timelines. Built entirely with vanilla JavaScript and HTML5 Canvas, it runs locally in your browser—no backend or database required.

## 🌟 Key Features

### ⏱️ Navigation & Scaling
* **Infinite Pan & Zoom:** Navigate smoothly through thousands of events via mouse, scroll, or touch gestures.
* **Dual Calendar Scales:** View the standard Gregorian calendar alongside specialized secondary rulers (e.g., the Ancient Hebrew observational calendar).
* **Date Calculator:** Built-in tool to accurately add or subtract durations across BCE/CE boundaries.

### 📅 Advanced Event Tracking
* **Precision Dating:** Log events down to the exact year, month, day, hour, and minute.
* **Milestones & Spans:** Plot single-point historical moments or duration-based spans.
* **Granular "Circa" Fades:** Visually represent uncertain dates with fading gradients, configurable down to specific days of uncertainty.

### 🗂️ Organization & Data
* **Hierarchical Lanes:** Organize events into collapsible, color-coded groups and sub-categories.
* **Rich Media Cards:** Attach context, images (with built-in slideshows), source links, and map URLs to any event.
* **Comparison View:** Select up to 3 events simultaneously to compare their details side-by-side.
* **Data Portability:** Auto-saves to your browser's Local Storage. Backup or share projects via **JSON export/import**.
* **Bulk CSV Import:** Rapidly populate timelines by mapping your CSV data directly to the canvas.

### 🎨 Customization
* **Built-in Themes:** Toggle instantly between Dark and Light modes.
* **Exhaustive UI Editor:** Tweak fonts and 11 specific UI color variables directly from the settings panel.

---

## 🚀 Quick Start

Because LOOM Timelines is a single-file application, installation is instant:

1. Download or clone `index.html`.
2. Double-click the file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Start building!

> **Note:** An internet connection is required on first load to fetch Tailwind CSS and Lucide Icons from their CDNs.

---

## 💡 Basic Usage Guide

| Action | How-To |
| :--- | :--- |
| **Navigate Canvas** | Click and drag the background to pan. Use your scroll wheel (or pinch on touchscreens) to zoom in and out. |
| **Create Events** | Click the **+ EVENT** button in the top menu. Fill in the timing data and assign it to a Lane. |
| **Manage Categories** | Click the **GROUP** button to make a root lane. Click the three-dot menu on any lane header to add sub-lanes or change colors. |
| **View Details** | Click any event plotted on the canvas to open its data card at the bottom of the screen. |
| **Import Data** | Click the **Spreadsheet Icon** in the top menu to view the expected column format and upload your CSV data. |
