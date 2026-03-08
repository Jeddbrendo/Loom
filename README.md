# LOOM Timelines

LOOM Timelines is a powerful, standalone, single-file HTML web application for creating, visualizing, and managing complex historical timelines. Built entirely with vanilla JavaScript and HTML5 Canvas, it runs locally in your browser without requiring a backend or database.

## 🌟 Features

### ⏱️ Rich Visualization & Navigation
* **High-Performance Canvas:** Renders thousands of events smoothly using HTML5 Canvas.
* **Infinite Pan & Zoom:** Intuitive navigation using mouse drag, scroll wheel, or touch/pinch gestures.
* **Dual Calendar Scales:** View standard Gregorian dates alongside secondary historical/geological rulers:
  * Holocene (HE)
  * Roman (AUC)
  * Before Present (BP)
  * Islamic (AH)
  * Modern Hebrew (AM)
  * Ancient Hebrew (Biblical) with dynamic lunar-solar month approximation.
* **Dynamic Gridlines:** Toggleable grid snapping to easily align and track eras.

### 📅 Advanced Event Management
* **Milestones & Time Spans:** Create single-point events or duration-based spans.
* **"Circa" Support:** Visually represent approximate start/end dates with dynamic fading gradients.
* **Rich Media Integration:** Add descriptions, external map links, source URLs, and image galleries (includes built-in slideshow for multiple images).
* **Comparison View:** Select up to 3 events at once to compare their details side-by-side in the floating details panel.

### 🗂️ Organization & Data Portability
* **Hierarchical Lanes:** Organize events into collapsible root groups and sub-lanes. Assign distinct colors and icons to categories.
* **Local Storage:** All projects, events, and settings are saved automatically to your browser's local storage.
* **Multi-Project Support:** Create and switch between multiple timeline projects seamlessly.
* **JSON Export/Import:** Backup your projects or share them with others via JSON files. Export entire projects or specific lane groups.
* **CSV Bulk Import:** Quickly populate timelines by importing CSV files containing event data (Supports columns for Title, Start Year, End Year, Lane, Color, Image URLs, etc.). Download template available: Timeline_Template_Bulk.csv

### 🎨 Deep Customization
* **Dark & Light Modes:** Built-in theme toggling.
* **Exhaustive Theme Editor:** Customize 11 specific color variables for *both* dark and light themes (Backgrounds, Lanes, Text, Borders, Event Opacities) directly from the UI.
* **Custom Fonts & Accents:** Tailor the global font family and primary accent color to your preferences.

## 🚀 Quick Start

Because LOOM Timelines is a zero-dependency, single-file application, installation is incredibly simple:

1. Clone the repository or download the `LoomTimelines.html` file.
2. Double-click the file to open it in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Start building your timeline!

*(Note: An active internet connection is briefly required upon loading to fetch Tailwind CSS and Lucide Icons from their respective CDNs).*

## 💡 How to Use

* **Navigation:** Click and drag the canvas to pan. Use your scroll wheel to zoom in and out of specific eras.
* **Adding Events:** Click the **+ EVENT** button in the top menu. Fill out the title, year(s), and categorize it into a lane.
* **Managing Lanes:** Click the **GROUP** button to create a new category lane. Click the three-dot menu on any lane header to rename, delete, add sub-lanes, or change its color/icon.
* **Viewing Details:** Tap or click on any rendered event on the timeline to open the details panel.
* **Bulk Import:** Create a CSV with headers like `Title`, `Start Year`, `End Year`, `Description`, and `Image` and click the spreadsheet icon to instantly map your data. Negative numbers or "BC/BCE" appended to years will automatically map to the BCE timeline.

## 🛠️ Built With
* **HTML5 Canvas:** For hardware-accelerated rendering.
* **Vanilla JavaScript:** Zero frontend frameworks used for logic.
* **Tailwind CSS (CDN):** For fast, modern, utility-first UI styling.
* **Lucide Icons (CDN):** For clean, scalable SVG iconography.


