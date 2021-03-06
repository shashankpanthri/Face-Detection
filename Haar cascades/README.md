# Haarcascade Face Detection  ![python](https://img.shields.io/badge/python-3-blue) ![OpenCV](https://img.shields.io/badge/open-cv-yellowgreen) ![jupyter-notebook](https://img.shields.io/badge/jupyter%20-notebook-blue)

----------------------------
### ABOUT THE PROJECT
---------------------------

This will use haarcascade classifier to detect face in images and video.

----------------------------
### Haar Cascade Classifier
----------------------------

Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper,
 “Rapid Object Detection using a Boosted Cascade of Simple Features” in 2001. It is a machine learning based approach where a cascade function is trained from 
a lot of positive and negative images.

- Positive images – These images contain the images which we want our classifier to identify.
- Negative Images – Images of everything else, which do not contain the object we want to detect

More detailed explanation about model and its arguments is in the notebook.

For more in-depth explanation : https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_objdetect/py_face_detection/py_face_detection.html


----------------------------
### Files
----------------------------

1. classifier - contains the haar cascade classifier used.
2. sample images - some images to test the model on.
3. image_face_detection - the notebook with code on image face detection.
4. video_face_detecion - the notebook with code on video face detection.
5. readme - this file you are reading.
6. face_detection video - live detection video.

----------------------------
### Some sample image results
----------------------------

![1](https://user-images.githubusercontent.com/55807308/96685119-4d6fdc80-139a-11eb-9197-990a2b6797ac.jpg)

![2](https://user-images.githubusercontent.com/55807308/96685297-890aa680-139a-11eb-91cf-a6858f412008.jpg)

![3](https://user-images.githubusercontent.com/55807308/96685306-8c9e2d80-139a-11eb-8882-a644d6994667.jpg)

![5](https://user-images.githubusercontent.com/55807308/96701738-8f0a8280-13ae-11eb-974c-7003bd90ad01.jpg)

![6](https://user-images.githubusercontent.com/55807308/96701761-9467cd00-13ae-11eb-92db-28f7504f3d8a.jpg)

![7](https://user-images.githubusercontent.com/55807308/96701768-96319080-13ae-11eb-86da-34c2ab60a623.jpg)

![4](https://user-images.githubusercontent.com/55807308/96835328-131d4280-1461-11eb-822f-28c8f5d84944.jpg)



----------------------------
### Sample live-video results
----------------------------

![video_face_detection_gif](https://user-images.githubusercontent.com/55807308/96687313-58783c00-139d-11eb-9dd8-42a5cd5ed688.gif)


----------------------------
### Pros of using Haarcascade Classifiers
----------------------------

1. It is very fast and can process things almost at real-time on CPU.
2. Very simple architecture and easy to understand.
3. It is very efficient.

----------------------------
### Cons of using Haarcascade Classifiers
----------------------------

1. This method is not very accurate and requres a certain scenario i.e. face looking directly at the camera to work.
2. The reason it is working fairly well here is because we added some additional arguments to the default model to make it more accurate.
 If this was the default model, the accuracy would have been a lot less.
3. The biggest drawback is that it gives a lot of false positives i.e. detecting a face where there is no face.
4. Another big drawback is that it requires the face to be the most prominent in the picutre i.e. the face should be the biggest part of the photo.
5. As discussed above, it does not work with non-frontal images.

----------------------------
### Best use case for Haarcascade Classifiers
----------------------------

1. It is the best used when you are certain the face will be frontal i.e. looking directly at the camera. 
2. It can be used on selfie camera where the face is the major part of the image and is usually looking directly at the camera. 

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

