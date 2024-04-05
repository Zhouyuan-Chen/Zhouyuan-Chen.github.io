---
title: "Embedded Remeshing"
excerpt: "Remeshing and Simulation<br/><img src='/images/lego2.png' width='50%'>"
collection: portfolio
---

Embedded Remeshing means using the meshing method to insert a layer between multiple materials, and make materials embedded into a big mesh structure. This technique is very useful to produce a simulation-ready scene with segmented data.

In this project, I implemented the prototype and modified the algorithm. Later I participated in implementing it in 3D with the [wildmeshing-toolkit](https://github.com/wildmeshing/wildmeshing-toolkit).

You can find the whole story in our paper.(I will upload it later)


<!--
Embedded Remeshing means using the meshing method to insert a layer between multiple materials, and make materials embedded into a big mesh structure. This technique is very useful to produce a simulation-ready scene with segmented data.

There is an application example(you can find the whole story in our paper):

For instance, we have a NeRF data:

<img src='/images/lego3.png' width='40%'>

Then you use some software(3D Slicer) to do volumetric segmentation, you don't need to worry about if your segmentation will create an ugly mesh since the Embedded Remeshing pipeline will help you heal your segmentation:

<img src='/images/lego4.png' width='40%'>

Finally, you set the initial setting for each segmentation with different labels, such as position, velocity, mass, etc. Throw them into the Embedded Remeshing pipeline, and you get the simulation result!

<img src='/images/lego2.png' width='40%'>

<img src='/images/lego.png' width='40%'>

I learned a lot about implementing remeshing in this project.

I want to write a note about the topology preserves for collapse operation later(If time allows me to do so). Because, in my opinion, it is the most tricky thing in this project.-->
