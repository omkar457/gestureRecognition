# Gesture Recognition using Neural networks(CNN/RNN)
Project to recognize  hand gesture using state of the art neural networks.

## Team
Omkar Joshi

## Problem Statement
Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

- Thumbs up:  Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backwards 10 seconds
- Right swipe: 'Jump' forward 10 seconds  
- Stop: Pause the movie

Each video is a sequence of 30 frames (or images)

## Understanding the Dataset
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 'train' and a 'val' folder with two CSV files for the two folders.

## Model Overview

Tried the following combinations
### Model 1 - 3D CNN with Batch Size - 20, IMG SIZE 120x120, Images per Video - 20, Epochs - 20
### Model 2 - 2D CNN + RNN(LSTMs) with Batch Size - 20, IMG SIZE 100x100, Images per Video - 20, Epochs - 20
### Model 3 - Transfer Learning + 2D CNN + RNN(LSTMs) with Batch Size - 20, IMG SIZE 120x120, Images per Video - 20, Epochs - 20
### Model 4 - Transfer Learning + 2D CNN + RNN(GRUs) with Batch Size - 16, IMG SIZE 80x80, Images per Video - 20, Epochs - 17
### Model 5 - 3D CNN with Batch Size - 24, IMG SIZE 160x160, Images per Video - 20, Epochs - 30
### Model 6 - 2D CNN + RNN(LSTMs) with Batch Size - 24, IMG SIZE 160x160, Images per Video - 20, Epochs - 30
### Model 7 - Transfer Learning + 2D CNN + RNN(LSTMs) with Batch Size - 24, IMG SIZE 120x120, Images per Video - 20, Epochs - 30
### Model 8 - Transfer Learning + 2D CNN + RNN(GRUs) with Batch Size - 24, IMG SIZE 120x120, Images per Video - 20, Epochs - 17¶


## Choosing model 4 as this has both high train and val accuracies. 
TL is able to extract most of the feature required for this gesture experiment compared to other models.


