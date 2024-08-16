*Live-Face-Detection Using Python* 

The project aim is to detect the human faces through live camera video stream using Laptop's / PC's Internal camera

*Learning Objectives :*

   1) To learn about Computer vision (A main branch in AI) through " OpenCV " which is an open-source-computer-vision library in python 
   2) To implement the ML Detection Models using python . In the context of  " vision " many open source libraries are available but most efficient models / libraries are provided by *MediaPipe , TenserFlow, OpenCV-Haar Cascades,Yolo*
  3) After completion of this project we will be familiar with other AI Computer Vision projects such as *Object detection , image classification , hand-landmark detection* etc..,

*Prerequisites :*

_1) Revise Python_ : Firstly go through the concepts in the python mainly take a deep look about implementation of class and objects , you can refer this python tutorial by " programiz " , we can easily recollect the basic from each concept using this : https://www.programiz.com/python-programming/class

_2) Effective Python IDE_ : We have to install effective python IDE , I will recommend " Pycharm"  , we can use multiple project files in the same platform and it has an AI assistant which can clarify errors and help in developing , Try to install it and after installation go through the UI options of IDE  

_3)Learning about Libraries_  :  Firstly install the required libraries in the inbuilt terminal in pycharm after creating project using below commands :
 *For OpenCv : pip install opencv-python* 
*For MediaPipe : pip install mediapipe*
After installation learn about basic classes and functions provided by those libraries in the web

*Implementation*

_1) Capturing live video frames_
 Focus on the streaming live frames using laptop/pc integrated camera , you can learn about this in the below documentation : 
https://www.geeksforgeeks.org/python-opencv-capture-video-from-camera/

_2)Sending frames to MediaPipe models_
Use the functions provided by the mediapipe to analyse the frames and to extract data . some basic information about mediapipe classes and functions :

Classes:
1)mp.solutions.face_detection.FaceDetection

Functions:
1)   init(self, model_selection=0, min_detection_confidence=0.5)
2)  process(self, image)

_3)Drawing results :_ 
Draw a boundary box around the face by using the data provided by the MediaPipe function based on the provided locations

*NOTE* 
It is the recommended and easy approach to build the project you can perform your own methods based on your knowledge
