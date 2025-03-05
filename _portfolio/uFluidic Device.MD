---
title: "uFluidic Device"
excerpt: "19 x 69 mm uFluidic Device sorting particles in the size range of 125 μm - 500 μm"
header:
  image: /assets/img/Linear Actuator Assembly Side View.png
  teaser: /assets/img/Linear Actuator Assembly Render Front.jpg
gallery:
  - url: /assets/img/Syringe Pump Top Down.jpg
    image_path: /assets/img/Syringe Pump Top Down.jpg
    alt: "Syringe Pump Top Down View"
  - url: /assets/img/Syringe Pump Circuit Diagram.jpg
    image_path: /assets/img/Syringe Pump Circuit Diagram.jpg
    alt: "Syringe Pump Circuit Diagram"

---

# Introduction
**Overview of Microfluidic Devices.**
Microfluidic devices are small-scale systems that manipulate fluids in channels with dimensions typically ranging from tens to hundreds of micrometers. These devices are widely used in fields like biomedical research, chemical analysis, and industrial applications due to their advantages in handling small fluid volumes, precise control of flow dynamics, and rapid processing times. The main benefits of microfluidic devices include:

* High throughput and efficiency in sample analysis.
* Reduced reagent consumption, making them cost-effective.
* Precise control over reaction conditions, improving consistency.
* Integration with sensors for real-time monitoring.

**What is Pinched Flow Fractionation (PFF) and How Does It Work?**
Pinched Flow Fractionation (PFF) is a microfluidic technique used for continuous size-based separation of particles. It utilizes a unique laminar flow profile within a microchannel to align and fractionate particles without the need for external forces (e.g., electric or magnetic fields).

**Principle of PFF**
* Flow Focusing: A sample fluid containing particles is introduced into a microchannel where a secondary fluid (without particles) is used to push the sample toward one sidewall in a narrow, pinched segment.
* Size-Based Separation: As the fluid enters a broader section of the channel, the laminar flow expands, and particles spread out based on their size. Larger particles experience a greater shift toward the center, while smaller particles remain closer to the sidewall.
* Collection of Separated Particles: The microchannel often has multiple outlets where particles are collected based on their final positions.

**Advantages of PFF**
* Continuous processing, unlike traditional batch separation techniques.
* No need for external forces, reducing system complexity.
* High precision in size-based sorting, applicable to biological and industrial samples.

**Application of PFF: Sorting of Small Particles in Biomedical Research.**
One significant application of PFF is in cell sorting for biomedical diagnostics. For example, PFF can be used to separate circulating tumor cells (CTCs) from blood samples, enabling early cancer detection. This method is non-invasive and allows for continuous monitoring of cancer progression by analyzing rare tumor cells in the bloodstream.

**Supporting Citation.**
A primary literature source discussing the principles and application of PFF is:

* Yamada, M., Nakashima, M., & Seki, M. (2004). Pinched Flow Fractionation: Continuous Size Separation of Particles Utilizing a Laminar Flow Profile in a Pinched Microchannel. Analytical Chemistry, 76(18), 5465-5471. [DOI: 10.1021/ac049863r]​
This study demonstrates the feasibility of using PFF for precise particle separation and highlights its potential in applications such as polymer bead separation, environmental monitoring, and biomedical diagnostics.

---

# Instructions
​Fabricating a microfluidic device involves several key steps, from designing the initial model to assembling the final functional device. Here's a detailed breakdown of each stage:​

1. **CAD Model.**
The process begins with creating a Computer-Aided Design (CAD) model of the microfluidic device. This digital blueprint defines the geometry, dimensions, and features of the microchannels and chambers. Software such as AutoCAD, SolidWorks, or specialized microfluidic design tools are commonly used. Precise modeling is crucial to ensure that the final device functions as intended.​

2. **Print and Cure Mold.**
Once the CAD model is finalized, it's used to fabricate a mold, which serves as a template for the microfluidic channels. 3D printing technologies, like stereolithography (SLA) or digital light processing (DLP), are often employed due to their high resolution and accuracy. The chosen resin is cured layer-by-layer using a light source, solidifying the material to form the mold. After printing, the mold undergoes a post-curing process to enhance its mechanical properties and ensure complete polymerization.​

3. **Parylene Coating.**
To facilitate the release of the polydimethylsiloxane (PDMS) from the mold and to improve the surface quality of the microchannels, a thin layer of Parylene is deposited onto the mold. Parylene is a biocompatible polymer applied through a chemical vapor deposition process, creating a uniform, pinhole-free coating. This step is essential to prevent PDMS adhesion to the mold, ensuring clean demolding and preserving the integrity of the microstructures.​

4. **Cast PDMS.**
PDMS, a silicone-based elastomer, is prepared by mixing its base and curing agent in a specific ratio (commonly 10:1). This mixture is poured over the Parylene-coated mold, ensuring it covers all features without air bubbles. Degassing in a vacuum chamber removes trapped air, which is crucial for maintaining the fidelity of the microchannels. The PDMS is then cured, typically at 60–80°C for several hours, until it solidifies. Once cured, the PDMS layer is carefully peeled off from the mold, revealing the replicated microfluidic structures.​

5. **Plasma Bonding to Glass Slide.**
To seal the PDMS microchannels and create a functional microfluidic device, the PDMS layer is bonded to a glass slide. Both the PDMS surface and the glass slide are treated with oxygen plasma, which activates their surfaces by introducing hydroxyl groups. When brought into contact after plasma treatment, these surfaces form strong covalent bonds, resulting in a permanent, leak-proof seal. This bonding technique ensures the durability and reliability of the microfluidic device during operation.​

---

# Discussion

1. **Why Are Resin-Printed Molds Coated with Parylene Prior to Casting PDMS?** Resin-printed molds are coated with Parylene before casting PDMS to improve demolding efficiency and prevent unwanted adhesion. Parylene is a chemically inert, biocompatible polymer applied through chemical vapor deposition (CVD), forming a thin, uniform layer that offers several benefits:
* PDMS can adhere to the surface of resin-printed molds, making it difficult to peel off cleanly. Parylene provides a non-stick, hydrophobic surface that facilitates easy demolding.
* The coating smooths out imperfections on the mold’s surface, ensuring well-defined microfluidic features with minimal roughness.
* The Parylene layer protects the mold from repeated use, preventing wear and deformation over multiple castings.
* It prevents unwanted reactions between PDMS and uncured residues in the mold, ensuring the PDMS replica maintains high fidelity.

2. **Hypothetical Applications of the Microfluidic Mixer or Sorter.** A microfluidic mixer or particle sorter has various applications in biomedical, chemical, and environmental research. Some potential applications include:
* Separation of cancer cells from blood samples for early detection.
* Sorting of engineered nanoparticles for drug delivery.
* Detecting and separating microplastics from water samples.
* Sorting biomolecules based on size for research and pharmaceutical applications.
* Using on-chip sorting to process biological samples for rapid disease detection.

3. **Why Is the Geometry Conducive to Sorting?** The efficiency of the sorting process depends on the microchannel's geometry, including:
* Forces particles to align against one wall before entering the expansion region, ensuring controlled size-dependent deflection.
* Allows particles to spread out based on size and flow characteristics.
* Designed to collect separated particle streams with minimal cross-mixing.
* The placement of sample and buffer inlets controls flow alignment and ensures particles enter the sorting region consistently. The gradual expansion of the channel amplifies small differences in particle positions, which results in precise size-based sorting.

4. **Steps Taken to Ensure Equal Flow Distribution at Outlets.** To maintain uniform flow rates at each outlet and prevent disruptions:
* Each outlet has equal widths and lengths to ensure even resistance and prevent biased flow.
* The ratio of sheath flow to sample flow is optimized to maintain consistent focusing of particles.
* The outlets are positioned equidistant from the expansion region to reduce pressure gradients.
* Used to verify streamline integrity and optimize flow balance.

5. **Future Improvements for Sorting Efficiency.** Based on experimental results, potential modifications include:
* Narrowing the pinch segment (<50 µm) may improve initial alignment and resolution.
* Modifying the sheath-to-sample flow ratio to improve particle focusing before sorting.
* Applying a hydrophobic coating to reduce particle adhesion and streamline disruptions.
* Instead of a sharp expansion, a gradual curved widening may reduce turbulence and improve separation accuracy.

---


# Multimedia

<iframe src="https://a360.co/43haqTf" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" frameborder="0"></iframe>

{% include gallery caption="uFluidic Device" %}
