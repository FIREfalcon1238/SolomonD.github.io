title: "Flag Football Attachment Generative Design"
excerpt: "A Fusion 360 Generative Design on my magnet Flag Football Attachment."
header:
  image: assets/img/1.jpg
  teaser: assets/img/3.jpg
gallery:
  - url: assets/img/4.jpg
    image_path: assets/img/4.jpg
    alt: "Force Philosophy"
  - url: assets/img/Screenshot 2025-04-23 160227.jpg
    image_path: assets/img/Screenshot 2025-04-23 160227.jpg
    alt: "Original CAD"
  - url: assets/img/Screenshot 2025-04-23 160302.jpg
    image_path: assets/img/Screenshot 2025-04-23 160302.jpg
    alt: "Original CAD Mate"
  - url: assets/img/Screenshot 2025-04-23 160401.jpg
    image_path: assets/img/Screenshot 2025-04-23 160401.jpg
    alt: "Gen Design CAD"
  - url: assets/img/Screenshot 2025-04-23 160429.jpg
    image_path: assets/img/Screenshot 2025-04-23 160429.jpg
    alt: "Gen Design CAD Mate"
  - url: assets/img/Screenshot 2025-04-23 160618.jpg
    image_path: assets/img/Screenshot 2025-04-23 160618.jpg
    alt: "Gen Design CAD Comparisons"
  - url: assets/img/Screenshot 2025-04-23 160738.jpg
    image_path: assets/img/Screenshot 2025-04-23 160738.jpg
    alt: "Gen Design CAD Mate Comparisons"
  - url: assets/img/IMG_0451.GIF
    image_path: assets/img/IMG_0451.GIF
    alt: "Pulling of Flag"
---

Introduction: Solving a Real Problem with Performance Innovation

In partnership with the Tennessee Titans, this project was aimed at reimagining a core piece of flag football equipment — the belt attachment system — to eliminate the failures of Velcro-based designs. The original prototype introduced a magnetic quick-release mechanism that addressed complaints from athletes and officials: unreliable detachment, discomfort, and breakage under strain.

While the first physical prototypes showed promise in testing, there were still key challenges to overcome:
* Accidental flag detachment
* Poor durability under player contact
* Difficult flag reattachment mid-game
* Weak resistance to twisting and angled forces
The solution? Use generative design to improve both performance and comfort, making the components lighter, safer, and more robust under real-world gameplay conditions.

**From Concept to Generative Design: Smarter, Stronger Components**
Two main components were optimized:
1. Belt-Side Attachment – anchors the magnet to the player’s belt
2. Flag-Side Attachment – mates with the magnet and releases under a clean pull
Both were redesigned using Autodesk Fusion 360’s Generative Design workspace, with constraints and forces applied based on how the system functions in action.

**Design Logic: Forces That Define the Geometry**
Belt-Side Attachment
This part had to remain secure to the belt while managing several forces:
* Shear force (parallel to the belt) when the flag is pulled
* Axial magnetic retention force to keep the flag attached during running and lateral movement
* Distributed compression force in the event a player falls or lands on it, which required a larger contact surface area to reduce injury risk

**Flag-Side Attachment**
The flag-side component carries similar force profiles but with a few key differences:
* It must release under a clean, angled pull, requiring a shape that balances axial force and shearing at a controlled angle
* It needs to survive sudden torsional force or impact if a player falls or twists the flag before releasing it
* Angle optimization was introduced in the generative setup to prevent breakage during off-axis pulls
By accounting for angled shear, magnetic retention, and fall impact, the generated geometry ensured reliable detachment without material fatigue or failure.

**Key Generative Design Parameters**
| Parameter                | Value                         |
|--------------------------|-------------------------------|
| Material                 | PA12 Nylon (SLS)              |
| Manufacturing Method     | Additive – Unrestricted (SLS) |
| Min Wall Thickness       | 1.0 mm                        |
| Overhang Angle           | 45°                           |
| Max Displacement (XYZ)   | 0.3 mm (Z: 0.2 mm optional)   |
| Objectives               | Minimize Mass + Structural Integrity |

**Performance Overview**
| Metric                    | Belt Attachment | Flag Attachment |
|---------------------------|------------------|------------------|
| Original Mass             | 22.3 g           | 18.7 g           |
| Generative Mass           | 12.1 g           | 10.2 g           |
| Pull Test (Shear/Peel)    | Passed @ 22N     | Passed @ 22N     |
| Drop & Torsion Durability | Passed           | Passed           |
| Gameplay Comfort          | Improved         | Improved         |
| Flag Reattachment Time    | ~4 seconds       | ~4 seconds       |

**Testing and Real-Use Validation**
Once the designs were finalized:
* FDM prototypes were printed for rapid fit testing
* Final versions were printed via SLS in PA12
* In-game simulations were run with intentional falls, pulls, and stress cycles
* Players found both components easier to use, more comfortable, and safer during impact
---

# CAD Model

<iframe src="https://a360.co/4lKqQu6" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

<iframe src="https://a360.co/4cm0aLU" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

**Testing and Real-Use Validation**
Using generative design not only reduced material but also allowed geometry to form around the way force flows through the part, which traditional CAD modeling couldn't replicate easily. It was especially helpful in: 
* Preventing overdesign
* Customizing force paths for durability
* Enabling additive-only geometries that feel almost organic


{% include gallery caption="Generative Design" %}

