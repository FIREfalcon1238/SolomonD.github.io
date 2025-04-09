---
title: "Bike Phone Mount/Holder"
excerpt: "A Phone Holder for Bike Handlebars, utilizing PLA, designed to function in any orientation."
header:
  image: assets/img/Bike_Phone_Holder_2025-Apr-09_02-38-22AM-000_CustomizedView411613111_jpg.jpg
  teaser: assets/img/Bike_Phone_Holder_2025-Apr-09_02-13-15AM-000_CustomizedView14103859916_jpg.jpg
gallery:
  - url: assets/img/Bike_Phone_Holder_2025-Apr-09_01-53-05AM-000_CustomizedView344892819_jpg.jpg
    image_path: assets/img/Bike_Phone_Holder_2025-Apr-09_01-53-05AM-000_CustomizedView344892819_jpg.jpg
    alt: "CAD Render w/o Phone"
  - url: assets/img/Bike_Phone_Holder_2025-Apr-09_02-38-22AM-000_CustomizedView411613111_jpg.jpg
    image_path: assets/img/Bike_Phone_Holder_2025-Apr-09_02-38-22AM-000_CustomizedView411613111_jpg.jpg
    alt: CAD Render w/ Phone"
  - url: assets/img/Screenshot 2025-04-08 213616.jpg
    image_path: assets/img/Screenshot 2025-04-08 213616.jpg
    alt: "Cross Section of Screw Mechanism"
  - url: assets/img/IMG_9178.jpeg
    image_path: assets/img/IMG_9178.jpeg
    alt: "Previous Iteration Only Using PLA"

---

3D-Printed Bike Phone Holder Design

**Top-Down Modeling & Its Role**
This phone holder design leveraged top-down modeling, a technique where the overall system is conceptualized first, and individual components are created with reference to each other. This method ensured that all parts of the phone holder assembly—clamp, rotational joint, and phone grip—fit together seamlessly from the start.
By referencing common geometry and setting master sketches at the top level, this approach allowed for adjustments to be made at the assembly level without causing mismatches between parts. For instance, if the phone dimensions or bar diameter changed, it was simple to propagate those updates across the entire assembly. Top-down modeling gave me better control over clearances, alignment, and proportions during every step of the design.

**Design Rationale**
The goal was to create a user-friendly phone holder that could quickly switch between portrait and landscape orientations while being easy to mount and adjust on a bike. Many phone holders on the market require tools to reorient or reposition. My approach incorporated a screw rotation mechanism that allows the user to rotate the phone holder freely with minimal effort, ensuring both security and flexibility during use. The design is minimal yet functional, with ergonomic knobs for easy hand tightening.

**Rotation Mechanism**
At the heart of this design is a threaded screw rotation mechanism. It includes a ribbed dial that connects the phone grip to the clamp arm, allowing the user to twist and adjust the orientation. The screw provides firm resistance, preventing unwanted shifts while riding. The mechanism works reliably, maintaining angle stability over time due to well-fitted threads and material friction from PLA.

**Dimensional Adjustments for 3D Printing**
Throughout the process, several dimension changes were made to optimize the design for FDM 3D printing. For instance, hole diameters for screws were adjusted to account for shrinkage and over-extrusion, ensuring the threads could engage properly. Clearances were also added around interlocking parts to allow smooth rotation and assembly after printing. The clamp screws, in particular, required re-sizing to avoid overly tight fits, while still allowing the user to adjust tightness on various bike handlebar diameters.

**Printing Technology & Material**
The entire phone holder was printed using Fused Deposition Modeling (FDM) technology with PLA filament. PLA was chosen due to its:
* High dimensional accuracy
* Low warping tendency
* Ease of printing
* Sufficient durability for day-to-day use
PLA made it easy to print complex geometries like threads and curved grips without requiring post-processing or support removal hassles. The relatively quick print time also made it ideal for rapid prototyping and testing.

**Assembly and Use Instructions**
* Clamp Assembly: Begin by twisting the clamp knob to open the mechanism. Place the clamp around your bike handlebar and secure it by tightening the screws into the bottom holes until snug.
* Attach Phone Holder: Slide the phone holder's threaded socket onto the clamp screw. Twist the center knob to secure the grip's position.
* Adjust Orientation: To switch between portrait and landscape, gently twist the holder back and forth. The rotation mechanism will lock your phone in place once aligned.
* Insert Phone: Slide your phonee down from the top to fit your phone and hold securely.

**Printing Summary**
All parts were printed using PLA filament on an FDM printer. This was the best option for this project due to its strength, reliability, and ease of use. No supports were needed, and each component printed with minimal warping and high surface quality.

---

# CAD Model

<iframe src="https://a360.co/4cm0aLU" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

---

{% include gallery caption="Bike Phone Mount/Holder" %}

