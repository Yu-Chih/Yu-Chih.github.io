---
title: "Mechanical Design Projects"
layout: single
permalink: /mech/
author_profile: true
toc: true
gallery:
  - image_path: /assets/images/cart.jpg
    alt: "cart"
    title: "Air-propelled cart"
  - image_path: /assets/images/cfd.png
    alt: "ANSYS analysis"
    title: "Propelling force simulation"
gallery2:
  - image_path: /assets/images/fan_compilation.jpg
    alt: "fan"
gallery3:
  - image_path: /assets/images/CAM_tooling_path.jpg
    alt: "CAM tooling path"
gallery4:
  - image_path: /assets/images/CAM_product.jpg
    alt: "CAM product"
---
<style>
.default {
    /* font-weight:700; */
    font-size: 18px;
}
video.displayed {
    display: block;
    margin-left: auto;
    margin-right: auto }
p + ul {
    margin-top: -10px;
}
</style>

### CAM (Computer-aided manufacturing) project
<div class="default">
<p> Design a CAD profile and simulate the manufacturing process.</p>
<ul>
<li>Compare different tooling path and evaluate their efficieny.</li>
<li>Select the suitable tooling path from roughing to finishing.</li>
</ul>
</div>
{% include gallery id="gallery3"  caption="Fig1. Tooling process." %}
{% include gallery id="gallery4"  caption="Fig2. CAD design vs. Simulated end product." %}

### Air-propelled line tracing cart - Fan structure design
<div class="default">
<p> Make a cart that can follow a guiding line and is propelled by a fan.</p>
<ul>
<li>Design the fan structure with aerodynamics airfoil profile data.</li>
<li>Simulate the propelling force with ANSYS.</li>
<li>Prototpye the fan structure with 3D printing.</li>
</ul>
</div>

{% include gallery id="gallery" layout="half" caption="Fig1. Air-propelled cart.&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp; Fig2. ANSYS simulation." %}
{% include gallery id="gallery2" caption="Fig3. Fan airfoil profile.&emsp;&emsp;&emsp;Fig4. Fan CAD design.&emsp;&emsp;&emsp;Fig5. 3D-printed fan." %}