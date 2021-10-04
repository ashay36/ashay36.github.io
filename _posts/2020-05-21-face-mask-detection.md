---
layout: post
title:  "COVID-19 Face Mask Detection"
author: Ashay
categories: [ Deep Learning, Image Classification, Projects ]
image: assets/images/face_mask.jpg
---

A deep learning based model that detects whether a person is wearing a face mask or not with nearly 100% accuracy.

```
Framework : Keras

Pretrained model used : MobileNetV2

Trainable parameters : 3M

Number of classes : 2

Train Accuracy : 99.29%

Validation Accuracy : 100%
```

# Dependencies
<ul>
  <li> <a href="https://www.tensorflow.org/">Tensorflow</a> </li>
  <li> <a href="https://www.keras.io/">Keras</a> </li>
  <li> <a href="https://www.opencv.org/">OpenCV</a> </li>
  <li> <a href="https://www.numpy.org/">NumPy</a> </li>
</ul> 

# Overview

<b> Techniques used to reduce overfitting :- </b>
<ul>
  <li> Data Augmentation </li>
  <li> BatchNormalization </li>
  <li> Dropout </li>
  <li> Early Stopping </li>
</ul> 

Click <a href="https://github.com/ashay36/COVID-19-Face-Mask-Detection-">here</a> to checkout the code.

<b> To run the code :- </b>
<ul>
  <li>For training refer <i><b>mask_detection.ipynb</b></i></li>
  <li>For testing on your own image run <i><b>detect_facemask.py</b></i></li>
</ul> 
