---
layout: post
title:  "Face Applications"
author: Ashay
categories: [ Computer Vision, Deep Learning, Projects ]
image: assets/images/face_applications.jpg
---

This project contains face related applications using opencv and deep learning libraries.

#### Face Recognition using LBPH Face Recognizer

The pipeline involves the following steps :-
<ul>
    <li> Detecting faces using OpenCV's Haar Cascades </li>
    <li> Training a Face Recognizer using OpenCV's build-in LBPH Face Recognizer </li>
    <li> Saving the model and predicting on custom images </li>
</ul>

Click <a href="https://github.com/ashay36/Face-Applications/tree/master/Face%20Recognition%20using%20LBPHFaceRecognizer">here</a> to access the code.

#### Face Recognition using One Shot Learning

On a contrary to the above Face Recognition method which involves training on several images, One Shot learning only requires a pre-trained to directly get the embeddings from the detected face. The code involves the following steps :-
<ul>
    <li> Detecting faces using MTCNN Face Detector </li>
    <li> Getting feature embeddings of each class from pre-trained VGGFace model and storing them in a database </li>
    <li> Get the feature embeddings of the test image and calculate the distance between this test image and each embedding in the database </li>
    <li> If the distance is less than a threshold for a particular pair, then the identity has been found </li>
</ul>

Click <a href="https://github.com/ashay36/Face-Applications/tree/master/Face%20Recognition%20-%20One%20Shot%20Learning">here</a> to access the code

#### Face Alignment

It is one of the most important steps in modern day Face Recognition pipeline to increase the accuracy of recognition.

Click <a href="https://github.com/ashay36/Face-Applications/tree/master/Face%20Alignment">here</a> to access the code.

