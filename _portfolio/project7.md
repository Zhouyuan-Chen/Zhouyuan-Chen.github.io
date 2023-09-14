---
title: "Medical Oral Software -- Virtual Gums"
excerpt: "Acceleration and Reconstruction<br/><img src='/images/tooth/main.png' width='40%'>"
collection: portfolio
---

Virtual Gums is a medical software for dentists. I participated in developing and take care of two main parts of this software, collision detection and undercut generation.

For the collision detection, my duty is using accelerat structure and algorithms to make this process more faster(detect the collision between arbitrary two teeth, print out their distance and visualize the collision area.). The final version takes within 200 ms per computation. Comparing to the 2-3 min at the beginning, it is a giant improvement.(this is one of Virtual Gums's goal -- faster than existed Chinese medical softwares' collision detection's computation) 

For the undercut generation, my duty is designing a specific algorithm to generate the undercut model automatically. Due to I leave my bachelor school, this part code I have passed to senior students to maintain.

## Collision Detection Part Features：

* Detection of Collision Face Pairs and Edge Line Drawing

<img decoding="async" src="/images/tooth/collision.png" width="50%">

* Embed Deepth Visualization

<img decoding="async" src="/images/tooth/collsion2.png" width="50%">

* Calculation of Distance Between Teeth

<img decoding="async" src="/images/tooth/distance%20detect.png" width="50%">

* Performance

**this video may not fully display all funtions mentioned above, I will update video later...**

[![Video](/images/tooth/video%20poster1.png)](https://www.youtube.com/watch?v=SK7BsINxNnI)

## Restruction of Tooth Undercut Features

* Handmade Undercut

<img decoding="async" src="/images/tooth/undercut-example.jpg" width="50%">

* Original Tooth Model

<img decoding="async" src="/images/tooth/tooth%20model-non%20effect.png" width="50%">

* Undercut Generation Results

**note:Demonstration using the tooth mesh and the undercut mesh after calculation and export on MeshLab**

<img decoding="async" src="/images/tooth/undercut-final%20result.png" width="50%">

* Performance

[![Video](/images/tooth/video%20poster2.png)](https://www.youtube.com/watch?v=SK7BsINxNnI)
