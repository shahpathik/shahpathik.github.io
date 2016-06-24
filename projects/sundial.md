---
layout: project
type: project
published: true
image: images/sundial.jpg
title: Sundial Web Application
permalink: projects/sundial
date: 2013
labels:
  - Web Application
  - Java
  - Javascript
summary: A dynamic, customizable and useable sundial web application created by three undergraduate CS students for Software Engineering II.
---

<img class="ui medium right floated rounded image" src="{{ site.baseurl }}/images/micromouse-robot.png">

This sundial application was created by a team of three undergraduate software engineering students in 2013. This web application allows users to enter the desired date (using a date picker), location (it auto-generates the coordinates), and whether daylight savings should be activated or not. The application then generates an image of the sundial and gnomon, of the correct dimensions for these particular conditions. The user can then follow the instructions to print and cut out the images and paste them together to create their accurate sundial.

The code was divided into three parts: web design, calculations, and the drawing of the sundial. For this particular project, I focused on the drawing of the sundial, but in an earlier version, I coded the calculations as well. Both the drawing and the calculations are coded in Javascript.

By completing the project, I learned a few of the difficulties and conveniences of programming as a group using version control. I learned that communication is key, otherwise code will be written and rewritten more than it needs to be. I gained my first self-taught skills in Javascript, and I learned how a sundial actually works!
For this project, I was the lead programmer who was responsible for programming the various capabilities of the mouse.  I started by programming the basics, such as sensor polling and motor actuation using interrupts.  From there, I then programmed the basic PD controls for the motors of the mouse.  The PD control the drive so that the mouse would stay centered while traversing the maze and keep the mouse driving straight.  I also programmed basic algorithms used to solve the maze such as a right wall hugger and a left wall hugger algorithm.  From there I worked on a flood-fill algorithm to help the mouse track where it is in the maze, and to map the route it takes.  We finished with the fastest mouse who finished the maze within our college.

You can learn more and view the application at [the website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).
