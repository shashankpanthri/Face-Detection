# DNN Face Detection  ![python](https://img.shields.io/badge/python-3-blue) ![OpenCV](https://img.shields.io/badge/open-cv-yellowgreen) ![jupyter-notebook](https://img.shields.io/badge/jupyter%20-notebook-blue) ![Deep Neural Network](https://img.shields.io/badge/Deep%20Neural-Network-orange) ![caffe model](https://img.shields.io/badge/Caffe%20-Model-green)

----------------------------
### ABOUT THE PROJECT
---------------------------

This will use trained deep neural network to detect face in images and video.

----------------------------
### DNN Face Model
----------------------------

This is a new model that was included in the OpenCV version 3.3 . The more accurate OpenCV face detector is deep learning based, and in particular, utilizes the Single Shot Detector (SSD) framework with ResNet as the base network.
 The model was trained using images available on internet.

OpenCV provides two models for this:
1. Floating point 16 version of the original caffe implementation.
2. 8 bit quantized version using TensorFlow.

These notebooks only use the floating point 16 version of original caffe implementation.

When using OpenCV’s deep neural network module with Caffe models, you’ll need two sets of files:

- The .prototxt file(s) which define the model architecture (i.e., the layers themselves)
- The .caffemodel file which contains the weights for the actual layers

Both files are required when using models trained using Caffe for deep learning.

More detailed explanation about the model and its arguments is in the notebooks.

For more in-depth explanation : https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/


----------------------------
### Some sample image results
----------------------------

![1](https://user-images.githubusercontent.com/55807308/96829661-ba957780-1457-11eb-8b23-5c91df6fccc9.jpg)

![2](https://user-images.githubusercontent.com/55807308/96829678-bff2c200-1457-11eb-82a2-adc4399ac62f.jpg)

![3](https://user-images.githubusercontent.com/55807308/96829691-c4b77600-1457-11eb-968e-a32b0379babf.jpg)

![7](https://user-images.githubusercontent.com/55807308/96829711-cb45ed80-1457-11eb-9d22-326093e0c5d2.jpg)

![8](https://user-images.githubusercontent.com/55807308/96829715-cc771a80-1457-11eb-9d58-5148bc7d3b1e.jpg)

![9](https://user-images.githubusercontent.com/55807308/96829730-d4cf5580-1457-11eb-8d9e-4aa231852038.jpg)

![6](https://user-images.githubusercontent.com/55807308/96829740-d8fb7300-1457-11eb-9dc5-344635978456.jpg)


----------------------------
### Sample live-video results
----------------------------

![ezgif com-video-to-gif](https://user-images.githubusercontent.com/55807308/96834321-71492600-145f-11eb-91d4-b109868144e8.gif)

----------------------------
### Pros of using DNN face detector model
----------------------------

1. This is much better than Haarcascades in terms of detecting a face.
2. It does have false positives i.e. detecting a face where there is no face but that can be handled by varying the confidence threshold.
3. It runs on real-time on CPU.
4. It is not limited to frontal face like haarcascades and can work with different orientations like - up, down, left, right, side-face, etc.
5. It can detect a face on various scales and does not have the limitation of haarcascades which needs the face to be the most prominent thing in the frame. 

----------------------------
### Cons of using DNN face detector model
----------------------------

1. It is fast but it is not very accurate. 

----------------------------
### Best use case for DNN face detector model
----------------------------

1. If you are limited to only using CPU, this is the best method you can choose for face detection.=

----------------------------
### TECHNOLOGIES USED
----------------------------

- python
- openCV
- matplotlib

----------------------------
### REQUIREMENTS TO RUN THE PROJECT
----------------------------

Make sure you have these installed:

- python
- open cv
- matplotlib

