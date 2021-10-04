---
layout: post
title:  "Fruits Classifier"
author: Ashay
categories: [ Deep Learning, Image Classification, Projects ]
image: assets/images/fruits.jpg
---

A classifier that can classify up-to 120 different types of fruits and vegetables with 95% accuracy

```
Framework : Keras

Pretrained model used : VGG19

Trainable parameters : 8.37M

Number of classes : 120

Train accuracy: 97.39%

Validation accuracy : 95.64%
```

I have used VGG19 model pre-trained on the Imagenet dataset and fine-tuned it using Transfer Learning
technique.

Many different combinations of hyperparameters were experimented of which this model
proved to be more promising. The notebook also includes the code to unzip the dataset.

Techniques used to reduce overfitting : 
<ul>
  <li> Data Augmentation </li>
  <li> BatchNormalization </li>
  <li> Dropout </li>
  <li> Early Stopping </li>
</ul>  

Click <a href="https://github.com/ashay36/Fruits-Classifier/blob/master/fruits360_model.ipynb">here</a> to access the code.

Click <a href="https://www.kaggle.com/moltean/fruits" >here</a> to download the dataset.

