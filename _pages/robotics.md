---
permalink: /robotics/
title: "Robotics Projects"
layout: single
toc: true
gallery:
  - image_path: /assets/images/GUI.JPG
    alt: "GUI"
  - image_path: /assets/images/RoboDK.jpg
    alt: "Robot simulation"
---
<style>
.default {
    /* font-weight:700; */
    font-size: 18px;
}
.pink {
    font-weight:700;
    color: DeepPink;
}
.green {
    font-weight:700;
    color:LawnGreen;
}
.yellow{
    font-weight:700;
    color: Gold;
}
video.displayed {
    display: block;
    margin-left: auto;
    margin-right: auto }
p + ul {
    margin-top: -10px;
}
</style>

### Tool scripts for 3D-printing robot arm path planning
<div class="default">
<p> Write tool scripts to automate the robot arm path planning process.</p>
<ul>
<li>Create GUI for user input printing paramters (e.g. feed rate) and slicing paramters (e.g. hatch angle)</li>
<li>Automate the path generation process through RoboDK Python API</li>
</ul>
</div>
{% include gallery id="gallery" layout="half" %}

### Unicycle bots leader-follower formation control and collision avoidance
<div class="default">
<p> Design path planning algorith for unicycle bots with lead-followe formation.</p>
<ul>
<li>Implement A* algorithm and Dynamic window approach for the path planning of the leader bot.</li>
<li>Use artificial potential field for the following bots to maintain formation with collision avoidance.</li>
<li>Demo video:</li>
<ul>
<li>Leader bot <span class="pink">(pink)</span>: task assignment- from green triangle(start) to red triangle(goal)</li>
<li>Two following bots:</li>
<ul>
<li>bot2 <span class="green">(green)</span> </li> 
<li>bot1 <span class="yellow">(yellow)</span></li>
</ul>
note: local potential field showed in bot2 perspective</ul>
</ul>
</div>
<video class="displayed" width="480" height="360" controls muted>
<source src="/assets/files/Local potential map.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>