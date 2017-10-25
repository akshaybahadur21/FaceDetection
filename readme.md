## Face Detection using Haar Caascades	
This code helps you to understand and detect faces using webcam.


### Code Requirements
The example code is in Python ([version 2.7](https://www.python.org/download/releases/2.7/) or higher will work). 

### Description

Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. It is then used to detect objects in other images.

Here we will work with face detection. Initially, the algorithm needs a lot of positive images (images of faces) and negative images (images without faces) to train the classifier. Then we need to extract features from it. For this, haar features shown in below image are used. They are just like our convolutional kernel. Each feature is a single value obtained by subtracting sum of pixels under white rectangle from sum of pixels under black rectangle

###Haar features
<img src="https://github.com/akshaybahadur21/FaceDetection/blob/master/features.jpg">

OpenCV comes with a trainer as well as detector.


For more information, [see](https://docs.opencv.org/master/d7/d8b/tutorial_py_face_detection.html)

### Working Example

<img src="https://github.com/akshaybahadur21/FaceDetection/blob/master/trim.gif">


### Execution
To run the code, type `python Face.py`

```
python Face.py
```
