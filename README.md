#  2D Interactive Maker Studio

A lightweight, beautifully detailed 2D interactive workshop scene built entirely in a single HTML file. No external images, SVGs, or Canvas needed—everything is drawn using Pure CSS Art!

##  Features

* **Pure CSS Art:** The entire room, including the tools, plants, and machines, is drawn using CSS gradients, shadows, and shapes.
* **Animated Machines:** Features a working CNC, 3D Printer (with a solid enclosure), and Laser Cutter with smooth CSS keyframe animations.
* **Rich Environment:** Packed with geeky details like a pegboard, blueprints, a glowing laptop, and safety tape.
* **Interactive UI:** Click on any machine to open a sleek pop-up menu with links to manufacturing services.
* **Single File:** Everything is bundled into one easy-to-use HTML file.

##  How to Run

1. Clone or download this repository.
2. Double-click the `index.html` (or `workshop2d.html`) file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
3. That's it! No installation or server required.

##  How to Customize

To change the shop names and links that pop up when you click a machine, open the `.html` file in any text editor and scroll to the bottom. 

Find the `machineData` variable inside the `<script>` tag and edit the text and URLs:

```javascript
const machineData = {
    cnc: {
        title: "⚙️ CNC Machining Services",
        shops: [
            { name: "Your Custom Shop", url: "[https://your-link.com](https://your-link.com)" },
            // Add or edit more shops here
        ]
    },
    // ...
};
