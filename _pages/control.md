---
title: "System Control Projects"
permalink: /control/
layout: single
toc: true
author_profile: true
---
<style>
.default {
    /* font-weight:700; */
    font-size: 18px;
}
iframe.displayed {
    display: block;
    margin-left: auto;
    margin-right: auto }
p + ul {
    margin-top: -10px;
}
</style>

### Inverted pendulum controller design (LQR controller)
<div class="default">
<p> Design a controller to balance an inverted double pendulum.</p>
<ul>
<li>Perform system idenitfication experiments (white box, black box).</li>
<li>Design LQR controller with pole placement. </li>
<li>Demo video: </li>
</ul>
</div>
<iframe class="displayed" height="180px" src="https://www.youtube.com/embed/ZvjIXAaXdI0" title="SC42045 LQR controller (controller 1)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe>

### Motor position and speed control
<div class="default">
<p> Design different controllers for position and speed control of a loaded motor.</p>
<ul>
<li>Compare the position control performance of PID, lead controller designed using root locus and lead controller designed using bode plot.</li>
<li>Identify torque compensation for the asymmetric (L-shaped) load and perform an inverted pendulum control.</li>
<li>Demo video (L-shaped load inverted pendulum): </li>
</ul>
</div>
<iframe class="displayed" height="180px" src="https://www.youtube.com/embed/UHyqaVW4SHQ" title="Inverted Pendulum" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe>