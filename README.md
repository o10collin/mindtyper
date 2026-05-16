# mindtyper

An ultra-minimalist, single-file brain-dumping board designed for the web. Write text or double-click to instantly spawn raw ideas as draggable, floating nodes across a clean, distraction-free playground. 

Built entirely in a single standalone HTML file to run securely and natively on your domain with zero server architecture or database configurations.

---

## Key Features

* **Instant Digital Brain Dumping**  
  Type thoughts directly into the bottom input tray or double-click anywhere on the empty canvas void to spawn a note right under your cursor tip.
* **Physics-Based Fluid Pop Animation**  
  Newly spawned thoughts smoothly spring into view via a spring-like cubic-bezier ease curve, fading in organically.
* **Frictionless Spatial Organization**  
  Grab and drag thoughts freely to organize them spatially. Card coordinates wrap seamlessly with native browser window dimensions.
* **Integrated Theme Controller**  
  Quickly alternate backgrounds directly from the top navigation bar between a Solid Black Void, a Dotted Matrix, or a Drafting Wire Blueprint Grid.
* **Hybrid Editorial Typography**  
  The user interface components, buttons, menus, and input fields are rendered in high-weight **Montserrat** via a secure Google Fonts import, while your actual ideas remain isolated in crisp **JetBrains Mono**.
* **Dual-Language Native Localization**  
  Features an instant language selector component supporting English (`EN`) and German (`DE`) across all menu structures, forms, placeholder states, and right-click parameters.
* **Complete Session Persistence**  
  Automatically synchronizes your board layout configurations, active backgrounds, and active thought card highlight profiles directly into your browser's local storage.
* **High-Definition PNG Exporter**  
  Includes a built-in canvas capture tool to cleanly export your visual mind-maps out as high-quality `.png` layout images with a single click.

---

## Deployment

Because **mindtyper** is built entirely inside a single standalone document, deploying it takes less than a minute:

1. Upload your `index.html` file directly to your public web directory (e.g., via FTP, Vercel, Netlify, or GitHub Pages).
2. Access the URL via any modern desktop browser.

---

## Visual Controls & Shortcuts

* **Double-Click Canvas:** Instantly generates a clean blank card under your mouse pointer tip and auto-focuses text typing mode.
* **Right-Click Card:** Displays a custom embedded minimalist context menu allowing you to **Edit**, **Highlight** (toggles a bright block outline), or permanently **Delete** the chosen thought card.
* **Enter Key (During Input Entry):** Submits form data, spawns a new node into random coordinates on the board, and clears the input area cleanly.
* **Enter Key (During Inline Card Editing):** Instantly confirms typography alterations, saves the output data string, and cleanly blurs cursor focus away from the active block.
* **Clear Button:** Wipes the entire local memory landscape and clears out your canvas playground following a secure browser verification prompt.
