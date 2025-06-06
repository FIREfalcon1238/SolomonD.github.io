---
title: "3D Printed Print-in-Place Pliers"
excerpt: "A print-in-place (PIP) 3D printed pliers, utilizing PLA & TPU, designed to function straight out of the printer with minimal post-processing"
header:
  image: assets/img/IMG_9179 (1).jpeg
  teaser: assets/img/IMG_9179.jpeg
gallery:
  - url: assets/img/Pliers.png
    image_path: assets/img/Pliers.png
    alt: "Pliers Diagram"
  - url: assets/img/IMG_9189.gif
    image_path: assets/img/IMG_9189.gif
    alt: "Working Pliers"
  - url: assets/img/IMG_9185.gif
    image_path: assets/img/IMG_9185.gif
    alt: "Pliers Picking Up a Resistor"
  - url: assets/img/IMG_9178.jpeg
    image_path: assets/img/IMG_9178.jpeg
    alt: "Previous Iteration Only Using PLA"

---

This project showcases a print-in-place (PIP) 3D-printed pliers designed to function straight out of the printer with minimal post-processing. The defining feature is the built-in spring mechanism, which allows the pliers to snap open after closing. This innovative design leverages the flexibility of PLA while maintaining structural integrity for gripping tasks.

**What is Print-in-Place (PIP)?**
Print-in-place refers to 3D printing fully assembled objects without requiring additional assembly. This technique relies on precise clearances between moving parts, ensuring that hinges, gears, or in this case, a spring-loaded mechanism, work seamlessly post-print.

**Other Applications of Print-in-Place:**
* Hinged boxes – No need for separate lid attachments.
* Articulating figures – Toy snakes, dragons, and humanoid models with movable joints.
* Functional tools – Wrenches, pliers, and mechanical clamps.
* Mechanical chains – Ready-to-use chain links.

**Best Material Combinations for Print-in-Place**
* PLA: Great for detailed prints but limited flexibility.
* PETG: Slightly more flexible and durable.
* TPU: For truly flexible moving parts.
* Nylon: Excellent wear resistance for functional parts.

---

# CAD Model

<iframe src="https://a360.co/4bGMtXF" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

# Design & Iterative Process
**Spring Mechanism Design**
The Multi V-shaped spring in the middle is the heart of the design, providing the necessary force to push the handles apart once closed. This was achieved by:
* Using a thin cross-section in the spring arms to allow controlled flexing.
* Ensuring the material’s elasticity was sufficient but also stiff enough with multiple V-shaped springs to return to its original position.
* Keeping clearances tight but functional, ensuring smooth movement without fusing.​

**Iterative Improvements**
Early iterations suffered from overly loose springs that failed to provide enough force. As well as fusing between moving parts. Adjustments included:
* Thinning the spring arms for better flex.
* Increasing clearance to prevent fusing.
* Tweaking jaw angles for improved grip strength.
* Increasing V-shaped supports to increase stiffness.
* Deepened the pin connection between the Pliers and V-shaped supports for a stronger connection between the two.

**Pliers Specifications**
* Jaw Length: 31.2mm
* Jaw Capacity: 18.2mm
* Overall Length: 104mm
* Material Used: PLA & TPU
* Print Orientation: Flat on the bed

**Print Settings**
For best results, these print settings were used:
* Bed Adhesion: Brim (to prevent warping)
* Support: None (designed to be self-supporting)
* Print Speed: 50mm/s​

**Material: PLA**
* Layer Height: 0.3mm
* Wall Count: 3
* Infill Density: 15%

**Material: TPU**
* Layer Height: 0.2mm
* Wall Count: 2
* Infill Density: 25%

---

{% include gallery caption="3D Printed Print-in-Place Pliers" %}

