# search-and-rescue-drone
In this project the device has been built to detect the people from the aerial view through drone in natural disaster areas

>Device image 
![](IMAGES/drone_image.jpg)


**Overview**

* *The basic concept for this drone is to use computer vision to detect human beings from an Aerial view using quadcopters. We have realized that, while learning it would benefit us more if the work that we do is directed towards solving a social problem or helping society. Recent years of survey have shown that lives are getting endangered in natural and man-made calamities such as floods and fire.* 
------------------------------------------------------------------

Technical Details: The search and rescue drone have
two parts: 1) Neural network 2) Drone. 

1. Neural Network: The algorithm (Faster RCNN) is a computer vision deep learning method to
                   detect human being and shows the position in the image by making a rectangular box around
                   the detected human beings in the interface.
Executed by: TensorFlow, Python

2. Drone:
      a) (KK2.1.5, PixHawk) Flight Controller is being used to stabilize and control the quadcopter
         system.
      b) BLDC motor of 1800kV is being used whilst considering torque and lift for the chosen
         frame size paired with 30A ESC.
      c) Carbon fiber frame of size 250mm is being used.
      d) The whole system is powered by a LiPo battery, 3200mAh – 11.1V.
      e) FPV Camera of Resolution 700 TVL with Telemetry kit.

-----------------------------------------------------------------
Details of the project is ![here](docs/project_details.odt)

>**CITATION**

**Dataset citation :**
Pengfei Zhu, Longyin Wen, Xiao Bian, Haibin Ling and Qinghua Hu, arXiv 2018. Vision Meets Drones: A Challenge.

**Model Used:**
Keras RetinaNet of fizyr
https://github.com/fizyr/keras-retinanet
