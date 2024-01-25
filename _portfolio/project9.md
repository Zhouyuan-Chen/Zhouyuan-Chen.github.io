---
title: "Embedded Remeshing"
excerpt: "Geometry Processing, Remeshing, Simulation<br/><img src='/images/lego.png' width='40%'>"
collection: portfolio
---

This is my first project at NYU Geometric Computing Lab. Embedded Remeshing means using a method to insert a layer between multiple materials. This technique is very useful to produce a simulation-ready scence with a segmented data.

This is an example for the application:

For instance, we have a NeRF data:

<img src='/images/lego3.png' width='40%'>

Then you just use some software(3D Slicer) do volumetric segmentation, you don't need to take much time, since Embedded Remeshing pipeline will help you heal your segmentaion:

<img src='/images/lego4.png' width='40%'>

Finally, you set the initial setting for each segmentation with different labels, such as velocity, mass, etc. . Throw them into Embedded Remeshing pipeline, and you get the simulation result! So easy, right?

<img src='/images/lego2.png' width='40%'>

<img src='/images/lego.png' width='40%'>


I learnt a lot about implementing remeshing in this project.

I will publish my prototype toy program and the the project detail later. Oh, I will write a note about the topology preserve for collapse operation soon, the most tricky thing we encountered in this project, definitely!