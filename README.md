# cartoonifier-python-project

Aim: to build a python application that will transform an image into its cartoon using OpenCV.

Intro:
  Python is the pool of libraries. It has numerous libraries for real-world applications. One such library is OpenCV. OpenCV is a cross-platform library used for Computer Vision. It includes applications like video and image capturing and processing. It is majorly used in image transformation, object detection, face recognition, and many other stunning applications.


Installation:
  1 python3
  2 pip install numpy
  3 pip install matplotlib
  4 pip install opencv-python
  6 pip install easygui
  7 pip install imageio
  8 pip install tk

Method():
  1 fileopenbox(): The method in easyGUI module which returns the path of the chosen file as a string.
  2 cvtColor(image, flag): A method in cv2 which is used to transform an image into the colour-space mentioned as ‘flag’.
  3 resize(): resize the resultant image using the resize().
  4 imshow(): display image using imshow() method.
  5 medianBlur(): To smoothen an image, we simply apply a blur effect. This is done using medianBlur() function.
  6 plt.show(): plots the whole plot at once after we plot on each subplot.
  
Reference:
  https://data-flair.training/blogs/cartoonify-image-opencv-python/
  
