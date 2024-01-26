---
title: "Embedded Remeshing"
excerpt: "Geometry Processing, Remeshing, Simulation<br/><img src='/images/lego.png' width='40%'>"
collection: portfolio
---

Embedded Remeshing means using the meshing method to insert a layer between multiple materials, and make materials embedded into a big mesh structure. This technique is very useful to produce a simulation-ready scene with segmented data.

This is an example of the application:

For instance, we have a NeRF data:

<img src='/images/lego3.png' width='40%'>

Then you use some software(3D Slicer) to do volumetric segmentation, you don't need to take much time, since the Embedded Remeshing pipeline will help you heal your segmentation:

<img src='/images/lego4.png' width='40%'>

Finally, you set the initial setting for each segmentation with different labels, such as velocity, mass, etc. Throw them into the Embedded Remeshing pipeline, and you get the simulation result! So easy, right?

<img src='/images/lego2.png' width='40%'>

<img src='/images/lego.png' width='40%'>


I learned a lot about implementing remeshing in this project.

Oh, I will write a note about the topology preserve for collapse operation soon! Because, in my opinion, it is the most tricky thing in this project.
