---
layout: experience
title: Science and Creativity
active: exp-models
---

&emsp;&emsp;&emsp;&emsp;The Science and Creativity seminar was an introduction to what you can accomplish with basic skills and relatively cheap equipment. The course was very open ended with
the instructor’s main goals being that we create something new and we learn the basics of how we can make whatever we want in the future. We started with the basics of python programming and worked our way to writing code to interact with microcontrollers from a raspberry pi, how to do 3D design and even soldering.

&emsp;&emsp;&emsp;&emsp;Even though I was very familiar with the programming that we learned at the start of the course, I was still able to learn a ton from this class. I learned what it takes full working systems as well as how to read technical documents and determine if a microcontroller will do what I need it to do. Something that was completely new to me was doing 3D design and printing. We were lucky enough to have a 3D printer at our disposal, this allowed us to iterate and design whatever we needed for our projects.

&emsp;&emsp;&emsp;&emsp;This seminar was extremely rewarding as it showed me that I can create whatever I need and that I don’t need to rely on existing products or ideas.

<br>
<hr>

<h2> Personal Project </h2>

&emsp;&emsp;&emsp;&emsp; For my project, I decided to create a system that would take pictures of a dart board and automatically give the score of the darts on the board. This idea was a little aggressive given the timeline of the project so I just managed to create a prototype. The prototype consisted of a 3D printed enclosure that held a raspbery pi zero that had a camera attached. The enclosure was then hung on the ceiling above the dart board and the user could ssh into the raspberry pi and take images of the dart board. The images and their scores were then used as training data to create a neural network that attempted to use common patterns in the image data to hopefully output a score. The system could preform around 70% accuracy at its very best. I plan to iterate on this in the future, either by adding more cameras or improving picture quality to hopefully create a stronger model.

{% include single_centered_mp4.html src="/assets/science/Carlson-FinalPresentation.mp4"%}