# Moving Object Removal
The project goal is to analyze an input video and return the static background of the scene comprehensive of small dynamic changes over time. The algorithm is supposed to work properly both with input from a static camera and with a free moving camera (dynamic shot). Also, the algorithm works on-the-fly without preassumptions or preprocessing of the video frames.

The project make use only of image processing (CV) techniques and doesn't rely on ML models.

**Static**

![static](res/MovingObjectRemoval_1.gif)

**Dynamic**

![dynamic](res/MovingObjectRemoval_2.gif)

**Many objects**

![many objects](res/MovingObjectRemoval_3.gif)
