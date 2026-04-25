# FACE-MASK-DETECTOR-USING-CNN
FACE MASK DETECTOR USING CNN

INTRO:
Detects whether a person is wearing a face mask using real time webacam input /live video  .

Structure :-

1)DATASET:Uses a dataset with 1915 with mask images and 1918 without mask images

2)MASK DETECTOR :- This part of the model is trained on a dataset .It determnines whether an image has a mask or not.It uses a pretrained MOBILENETV2 and imagenet weights and biases

3)FACE DETECTION:-Detects a face when video input/webcam is turned o.It uses openCV 

4)Anaconda :-For setting up the live webcam/video input environmwnt

Working:
Mask detector trains on the images in dataset to learn mask detection.Face detector learns to find human face in a video input
Integration of mask detector and Face detector allows us to detect whether a person in the video input is wearing a mask or not
