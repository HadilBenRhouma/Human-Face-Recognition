README FILE:
In this beginner’s project, we will learn how to implement real-time human face recognition.
We will build this project in Python using OpenCV.
We will study the Haar Cascade Classifier algorithms in OpenCV. 
Haar Cascade Classifier is a popular algorithm for object detection.

Face Recognition is a technology in computer vision. In Face recognition / detection we locate and visualize the human faces in any digital image.
It is a subdomain of Object Detection, where we try to observe the instance of semantic objects. These objects are of particular class such as animals, cars, humans, etc. Face Detection technology has importance in many fields like marketing and security.

Cascade Classifiers and Haar Features:
Cascade Classifiers and Haar Features are the methods used for Object Detection.
It is a machine learning algorithm where we train a cascade function with tons of images. These images are in two categories: positive images containing the target object and negative images not containing the target object.
There are different types of cascade classifiers according to different target objects. In our project, we will use a classifier that considers the human face to recognize it as the target object.
Haar Feature selection technique has a target to extract human face features. Haar features are like convolution kernels. These features are different permutations of black and white rectangles. In each feature calculation, we find the sum of pixels under white and black rectangles.

Haar-cascade Detection in OpenCV:
OpenCV provides pre-trained models on Haar features and Cascade classifiers. These models are located in OpenCV installation.


Steps to implement human face recognition with Python & OpenCV:
1. Imports
2. Initialize the classifier
3. Apply faceCascade on webcam frames
4. Release the capture frames
5. Run the project file using
