# A computer vision based vehicle detection and counting system – AI Project

## Introduction

In many cities around the world, traffic issues are an important concern. The traffic problem has many big causes. Due to better health care, better education, better job opportunities, and well-built houses people migrate from rural to urban areas. And the number of residents moving to urban areas has increased dramatically, resulting in a drastic rise in the number of vehicles. Due to increasing the number of residents, the capacity of the roadway has become inadequate and has grown relatively slow. In large cities, this causes roads and the number of vehicles to be imbalanced which results in road congestion. Similarly, public transportation causes the same problem. Another factor, due to the lack of real-time traffic information causes inadequate traffic management. So, in an intelligent transportation system, especially for traffic management, vehicle detection and counting system plays an important role.

Note: In the future, the traffic problem causes a serious problem if not addressed appropriately.

This tutorial proposes a video-based approach based on computer vision technologies for vehicle detection and counting. To find foreground objects in a sequence of video, the suggested method uses a technique called background subtraction technique. Several computer vision techniques, including thresholding, hole filling, and adaptive morphology operations, are then applied in order to track moving vehicles more accurately and precisely. Finally, with the use of a virtual(simulated) detection zone, vehicle counting and tracking is conducted.

This is a simple vehicle detection project using Computer Vision..

Here I used background subtractions methods of OpenCV Library of Python and some morphological transformation for accuracy.
But this is for only static cameras. 

At the corner of the video you can see the count of the vehicles which gets recorded
when they cross a predefined limit. For the calculation of the object coordinates and object ids I defined a class called vehicles.py

1. Just download the repository and unzip the file. <br>
2. Run the python program named <b> <i>  "main.py" </i> </b> <br>
3. Enjoy the Vechile Count Program

![counting_vechile](/uploads/68cce10dc77d121d476df63e4ee9475d/counting_vechile.PNG)

<h3>  Feel free to count real time Vechile. If you have a crazy idea, then pull request ☺ </h3>

<h1> !! THANK YOU !! </h1>
