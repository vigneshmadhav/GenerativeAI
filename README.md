This is completely a deep learning project entirely based on neural networks and I think Facial emotion recognition(FER) project is one of the classical projects in deep learning.

We all know facial emotions play a vital role in our day-to-day life. so, we need a system which is capable of recognising our facial emotions and able to act accordingly.

This project is the first step in that system.

me emotion -- ntr emotion

Here I trained the convolution neural network with kaggle facial emotion dataset. so that it learns patterns for each facial expression and able to detect facial emotions


I wrote a medium blog on this project. you can find here for quick understanding and insights.
Feel free to download, clone , fork the project.

Installation of python libraries:
keras with tensorflow as backend
OpenCV
numpy
pandas
matplotlib
DataSet:
In this project I used kaggle dataset i.e
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/overview
we can use a kaggle API to access and download that dataset.

Usage:
This project is in notebook format. I wrote the program in google colabs.

Google colabs is a cloud based notebook IDE which offers a free GPU and allows us to write python code snippets with ease. It is almost similar to jupyter notebook but slight variations. Some of the code snippets in the program is specific to google colabs. Dont get confuse.

In the notebook, I explain all the concepts, pipeline , terminology , functions which is involved in the program in a clear and concised manner. Even I also mention some of my insights , intuitions and observations in the project.
I document almost everything that is used in the program.
This notebook file is a complete wrapout of practical exposure, understanding and theory.


facial_Emotion_Recognition_using_cnn.ipnb --> main file
images folder --> consists of images to be tested and also contains screenshots of results of that images.
model.h5 --> saved weights of the model which is trained with 200 epochs
model.json --> saved architecture of the neural network.
haarcascade classifiers --> higly pretrained classifiers to detect faces.


The following is the results of the images. I also add the number of persons in the image and the relevant emojis to their emotions of the persons to create sense of feel.

multistar_emotion mb_emotion khans_emotions



Thanks, Hope you enjoy the project! :)
