# graspingIRB140
This code based in the GGCNN structure and repository developed by Douglas Morrison, Peter Corke and Jürgen Leitner in 2018 and described in their project: Closing the Loop for Robotic Grasping A Real-time, Generative Grasp Synthesis Approach. (https://github.com/dougsm/ggcnn)

The fin_pose file allows detecting the location in pixels, the angle and the width of the grasping hypotheses on an object or set of objects using the GGCNN network and having as input a depth image that is captured with the Kinect V1 sensor.

The APCStowing file contains the main routine for the automated movement of the IRB140 robot in a scenario of collection and storage of objects within a warehouse, based on the detection of the grasping hypotheses with a GGCNN (Generative grasping convolutional network).
