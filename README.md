# Monitoring and Evaluation of Yoga Posture

## _Table of Contents_

## [Introduction](https://github.com/Pramod-Krishna/Monitoring-and-Evaluation-of-Yoga-Posture#introduction-1)
## [PoseNet](https://github.com/Pramod-Krishna/Monitoring-and-Evaluation-of-Yoga-Posture#posenet-1)
## [Refrences](https://github.com/Pramod-Krishna/Monitoring-and-Evaluation-of-Yoga-Posture#refrences-1)
## [Acknowledgement](https://github.com/Pramod-Krishna/Monitoring-and-Evaluation-of-Yoga-Posture#acknowledgement-1)

# Introduction

## _IMPORTANCE OF YOGA DURING THIS PANDEMIC_
Yoga, is a word that became popular across the world in the last few years. Yoga is not only beneficial for the body but also for the mind. It helps to improve blood flow and helps in building mind clarity. For ages, yoga was known to be beneficial for our physical & mental health. It not only help us to stay calm but also help us to lose weight.

During this ongoing coronavirus pandemic, when we are all bound to live a restricted life under the constant fear of infection risks, it is natural for anyone to develop anxiety. The continuous flow of negative news, the inadequacy of daily resources, everything is adding to this growing anxiety and depression. Being confined at home for such long periods of time, can be mentally challenging for us. When our mind is flooded with the uncertainty of the future, we often experience sleepless nights causing fatigue. Many of us are unable to relax our mind during this time thereby increasing the stress on our minds. 

During this time, it is important to understand that mental health is very important for survival. To help with this growing level of anxiety and depression, we must lead a healthy lifestyle, stay connected to our loved ones, and practice yoga at home.

# PoseNet
Pose estimation refers to computer vision techniques that detect human figures in images and videos. The [PoseNet](https://github.com/tensorflow/tfjs-models/tree/master/posenet) model takes a processed camera image as the input and outputs information about keypoints. It can be used to estimate either a single pose or multiple poses. It also configures the model to have a higher accuracy at the expense of performance. The output stride determines how much the output is scaled down relative to the input image size. The higher the output stride, the smaller the resolution of layers in the network and the outputs.
At a high level, pose estimation happens in two phases: 
* An input RGB image is fed through a convolutional neural network.
* Either a single-pose or multi-pose decoding algorithm is used to decode poses, pose confidence scores, keypoint positions, and keypoint confidence scores from the model outputs.

_Keypoints_
All keypoints are indexed by part id. The parts and their ids are

![image](https://user-images.githubusercontent.com/54993262/120840126-7048ad00-c587-11eb-8d49-fcbb25cd2081.png)

Single-person Pose Estimation

![image](https://user-images.githubusercontent.com/54993262/120841083-af2b3280-c588-11eb-9aa0-5c332b13226e.png)

Multi-person Pose Estimation
![image](https://user-images.githubusercontent.com/54993262/120840620-1dbbc080-c588-11eb-833f-e86ccf7a8f19.png)

# Refrences 
[PoseNet](https://github.com/tensorflow/tfjs-models/tree/master/posenet)
[Tensor Flow Blog](https://blog.tensorflow.org/2018/05/real-time-human-pose-estimation-in.html)

# Acknowledgement
* Vikram Nag RC
* Disha Kulkarni















