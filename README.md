# AI-Virtual-Painter
This System will track your hand get its landmarks and then use the points to draw on the screen. Here, you can draw on your screen using your hand gesture created using OpenCV library in Python.

Basic Functionality (For non-programmers) :
1 : Variable Eraser thickness 
2 : Drawing circle
3 : Drawing rectangle 
4 : Drawing ellipse 
5 : Free Hand Writing 
6 : Two fingers up, clears the complete screen 
7 : Showing brush thickness on screen

Brief:
->This model utilizes MediaPipe's hand tracking functions to get hand landmarks(reference points) that enable the user to actually draw stuff on the screen.

->Libraries used: OpenCV, MediaPipe, os, numpy, time
->HandTrackingModule.py is actually a class with functions like hand-landmark detector, fingers-up check and much more. We have used an instance(detector) from this  class in our main program.
->Index finger tip's landmark is used to draw on the canvas.

->The steps and tacks have been explicitly mentioned in the comments of the code.



