###KhanAcademy Clone
##Overview
This project is a frontend clone of the Khan Academy homepage, created for educational purposes to practice web development skills. It replicates the visual layout and static components of the site using HTML, CSS, and minimal JavaScript, with all code and styles embedded in a single HTML file.
Purpose
The goal was to learn web development techniques by recreating the Khan Academy homepage’s UI, focusing on its structure, styling, and static assets, without implementing dynamic functionality or backend features.
Note: This project is for learning only and respects Khan Academy's intellectual property. It is not intended for commercial use or public hosting.
Cloning Process
The Khan Academy homepage was cloned through the following steps:
HTML Structure Extraction

The homepage’s HTML was inspected using browser Developer Tools (Chrome/Firefox).
The core structure, including the header, hero section, course cards, and footer, was manually copied to form the basis of index.html.
Unnecessary dynamic or backend-related elements (e.g., API calls, user authentication scripts) were excluded to focus on static UI.

CSS Styling

CSS styles were extracted from the website’s source via Developer Tools, focusing on layout, typography, and colors.
Styles were simplified and embedded directly in a <style> tag within index.html to avoid external dependencies.
Media queries were added manually to ensure responsiveness across desktop and mobile viewports, based on observations of the original site’s behavior.

Asset Integration

Images, icons, and other static assets (e.g., logos, course thumbnails) were downloaded using Developer Tools’ “Network” tab or manual saving.
Assets were organized in an assets/ folder and linked with relative paths in index.html (e.g., assets/logo.png).
File sizes were kept as-is, prioritizing functionality over optimization for this learning exercise.

Minimal JavaScript

Basic interactivity (e.g., button hover effects) was added using inline JavaScript within index.html.
No external libraries or complex scripts were included, as the focus was on replicating the visual UI rather than dynamic features.

Testing and Refinement

The cloned UI was tested locally by opening index.html in a browser.
Browser Developer Tools were used to verify responsiveness and fix layout issues (e.g., adjusting padding, margins).
Iterative tweaks were made to align the clone’s appearance with the original homepage, focusing on visual fidelity.

Project Structure
KhanAcademy_clone/
├── assets/                # Local images and icons
├── index.html             # Single HTML file with embedded CSS and JavaScript
└── README.md              # Project documentation

Outcome
The result is a static, single-file HTML page that closely mimics the Khan Academy homepage’s frontend UI, including its layout, colors, and typography. The clone is functional for learning purposes but lacks dynamic features (e.g., course search, user login) and is not optimized for production use.
Ethical Considerations

This project was created as a learning exercise and does not replicate Khan Academy’s content or functionality for commercial purposes.
All code and assets were manually gathered for educational use, respecting the original website’s terms of service and intellectual property.

License
This project is unlicensed and intended for personal learning only. Do not use or distribute without permission from Khan Academy for any derivative works.
Acknowledgments

Inspired by Khan Academy’s clean and educational UI design.
Built using only browser Developer Tools and manual coding, with no external AI or no-code platforms.

