# KhanAcademy Clone

## Overview
This project is a frontend clone of the Khan Academy homepage, created for educational purposes to practice web development skills. It replicates the visual layout and static components of the site using HTML, CSS, and minimal JavaScript.

**Note:** This project is for learning purposes only and respects Khan Academy's intellectual property. It is not intended for commercial use or public hosting.

---

## Purpose
The primary goal of this project was to:
- Gain hands-on experience in web development.
- Recreate the Khan Academy homepage’s UI, focusing on its structure, styling, and static assets.
- Practice using browser Developer Tools for HTML, CSS, and asset extraction.
- Learn responsive design techniques and basic interactivity using plain JavaScript.

---

## Cloning Process

### 1. HTML Structure Extraction
- The homepage’s HTML structure was analyzed using browser Developer Tools (Chrome/Firefox).
- Key sections such as the header, hero section, course cards, and footer were manually replicated in `index.html`.
- Dynamic or backend-related elements (e.g., API calls, user authentication scripts) were excluded to focus solely on the static UI.

### 2. CSS Styling
- CSS styles were extracted from the website’s source using Developer Tools.
- Focused on replicating layout, typography, and colors.
- Styles were simplified and embedded directly in a `<style>` tag within `index.html` to avoid external dependencies.
- Media queries were added manually to ensure responsiveness across desktop and mobile viewports, based on observations of the original site.

### 3. Asset Integration
- Images, icons, and other static assets were downloaded via the Developer Tools “Network” tab or saved manually.
- Assets were organized in an `assets/` folder for better structure.
- Relative paths (e.g., `assets/logo.png`) were used for linking assets in `index.html`.
- Asset file sizes were left unoptimized to prioritize functionality over performance for this learning exercise.

### 4. Minimal JavaScript
- Basic interactivity (e.g., button hover effects) was added using inline JavaScript in `index.html`.
- No external libraries or complex scripts were included, as the focus was on replicating static UI elements rather than dynamic functionality.

### 5. Testing and Refinement
- The cloned UI was tested locally by opening `index.html` in a browser.
- Browser Developer Tools were used to verify responsiveness and fix layout issues (e.g., adjusting padding, margins).
- Iterative tweaks were made to improve alignment and ensure visual fidelity with the original Khan Academy homepage.

---

## Project Structure
KhanAcademy_clone/
├── assets/                # Local images and icons
├── index.html             # Single HTML file with embedded CSS and JavaScript
└── README.md              # Project documentation


---

## Outcome
The final result is a static, single-file HTML page that closely mimics the Khan Academy homepage’s frontend UI. The project demonstrates:
- A high level of visual fidelity in terms of layout, colors, and typography.
- Responsiveness across desktop and mobile devices.
- Basic interactivity through minimal JavaScript.

This project serves as a valuable learning exercise for web development, focusing on frontend skills.

---

## Ethical Considerations
- This project was created as a learning exercise and does not replicate Khan Academy’s content or functionality for commercial purposes.
- All code and assets were manually gathered for educational use, respecting the original website’s terms of service and intellectual property.

---

## License
This project is **unlicensed** and intended for personal learning only. Do not use or distribute without permission from Khan Academy for any derivative works.

---

## Acknowledgments
- Inspired by Khan Academy’s clean and educational UI design.
- Built using only browser Developer Tools and manual coding, and AI code editors.
