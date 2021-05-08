# Realtime Sign Language Recognition

[Dataset](https://github.com/Mehulipal/CS299.0/tree/master/Tensorflow/workspace/images) <br />
[Presentation](https://docs.google.com/presentation/d/1XM7BttTLwyz4IMS_ygr9sam1osl4HuetDxsfcgtwHNA/edit?usp=sharing) <br /> 
[Demo Video](https://drive.google.com/file/d/1poRH4IyNf_sbb4NMw9iq-1fpz9WsCn5W/view?usp=sharing)

## Technique Used
Transfer Learning using SSD MobileNet V2

## Problem Statement
Communication is a two-way process. But unfortunately, there always remains a barrier of communication between a deaf and dumb person and a normal person. There are many available speech recognition techniques to transcribe whatever the normal person speaks to the deaf and dumb person by converting speech to text but it really becomes difficult for a normal person to understand whatever the deaf and dumb person tries to express. On these grounds, this project aims to implement sign language recognition techniques so that the gestures of the deaf and dumb person becomes understandable to the normal person.

## Procedure
1. Collected images and labeled them using OpenCV & LabelImg
2. Using Transfer Learning (SSD MobileNet V2) & Tensorflow Object Detection API, trained a Deep Learning model
3. Converted the model to Tensorflow.JS Graph Model format & hosted it on IBM Cloud
4. Using React & Tensorflow.JS Computer Vision, made realtime sign language detections

## References
To be added...

## Setting Up
- Execute the following command in git bash
```
 git config --global http.postBuffer 524288000
```
- git config --global http.postBuffer 524288000
- Fork and Clone the [repository](https://github.com/Mehulipal/CS299.0)
- Download and Install [Node.js](https://nodejs.org/en/download/)
- Navigate to [Computer Vision](https://github.com/Mehulipal/CS299.0/tree/master/ComputerVision) directory
- Execute the following commands in terminal
```
npm install .
npm start
``` 
It will open the app locally

## Screenshot
<img src="https://i.ibb.co/jMD5kqC/Untitled3-COLLAGE.jpg" alt="Untitled3-COLLAGE" border="0" width="1000">
