---
layout: post
title:  "Wheat Detection"
author: Ashay
categories: [ Deep Learning, Object Detection, Competitions ]
image: assets/images/wheat.jpg
---

The competition was hosted on Kaggle.
The task was to detect and localize wheat heads in images.

```
Team Name : The Alphas

Authors : Ashay Ajbani and Pritam Rao

Competition Type : Object Detection

Framework : PyTorch

Solution Type : Transfer Learning

Number of Classes : 1

Pretrained Models Used : 
1) Detection Transformer (Submission 1)
2) Efficient Detector (Submission 2)

Public Leaderboard Rank : 481/2270

Private Leaderboard Rank : 354/2270
```

### Our Approach

**Submission 1** : 

For our first submission, we fine tuned pretrained *Efficient Detector* model for our problem.
It gave us a score of 0.7331 on the public leaderboard. 

Click <a href="https://github.com/ashay36/Machine-Learning-Competitions-Notebooks/tree/master/Kaggle%20-%20Global%20Wheat%20Detection/Efficient%20Detector">here</a> to access the code

The file *wheat_detection_efficientdet.ipynb* includes training as well as inference. We have used Test Time 
Augmentation and Weighted Boxes Fusion for making more accurate predictions.

**Submission 2** :
 
For our second submission, we fine tuned pretrained *DETR* model for our problem. It gave us a 
score of 0.5758 on the public leaderboard. 

Click <a href="https://github.com/ashay36/Machine-Learning-Competitions-Notebooks/tree/master/Kaggle%20-%20Global%20Wheat%20Detection/DEtection%20TRansformer%20(DETR)">here</a> to access the code

We have uploaded the following DETR notebooks :
 
 1) *wheat_detection_detr_training.ipynb* : Includes processing the dataset and training on DETR.

 2) *wheat_detection_detr_inference.ipynb* : Making predictions on the test images using the trained model.

We have documented the notebooks so that you can easily reproduce the results.
