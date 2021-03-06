---
layout: post
title:  "Emergency Vehicle Classification"
author: Ashay
categories: [ Deep Learning, Image Classification, Competitions ]
image: assets/images/vehicle.jpg
---

The competition was hosted on Analytics Vidhya.
The task was to classify vehicles into emergency and non-emergency categories.

```
Team Name : The Alphas

Authors : Ashay Ajbani and Pritam Rao

Competition Type : Image Classification

Framework : Keras

Solution Type : Model Ensembling

Number of Classes : 2

Pretrained Models Used : VGG16 and NASnet Large

Private Leaderboard Rank : 36/10000
```

### Our Approach
We ensembled 5 models to make final predictions. 

**Models** : 
<ul>
<li> Model 1 : Fine Tuning VGG16 </li>
<li> Model 2 : Fine Tuning VGG16 with l2 regularization </li>
<li> Model 3 : k-fold validation </li>
<li> Model 4 : Fine Tuning NASnet </li>
<li> Model 5 : Fine Tuning NASnet with l2 regularization</li>
</ul>

The predictions taken by ensembling above 5 models
resulted in an accuracy greater than any of the individual models. 

Techniques used to reduce overfitting : 
<ul>
  <li> Data Augmentation </li>
  <li> BatchNormalization </li>
  <li> Dropout </li>
  <li> l2 Regularization </li>
</ul> 

**Accuracy** : 
<ul>
<li> Model 1 : 0.9498 </li>
<li> Model 2 : 0.9546 </li>
<li> Model 3 : 0.9444 </li>
<li> Model 4 : 0.9548 </li>
<li> Model 5 : 0.9514 </li>
<li> After Ensembling (final) : 0.9688 </li>
</ul>

Click <a href="https://github.com/ashay36/Machine-Learning-Competitions-Notebooks/tree/master/Analytics%20Vidhya's%20Computer%20Vision%20Competition">here</a> to access the code