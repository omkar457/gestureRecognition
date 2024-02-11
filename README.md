# Gesture Recognition Project

Gesture Recognition Project - To predict the actions based on a gesture.

## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusion](#conclusion)
* [Contact](#contact)

## General Information

Develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

* Thumbs up:  Increase the volume
* Thumbs down: Decrease the volume
* Left swipe: 'Jump' backwards 10 seconds
* Right swipe: 'Jump' forward 10 seconds  
* Stop: Pause the movie

Dataset: [Dataset](https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL)

Paried team members:

## Technologies Used

* Tensorflow=2.13.0
* Keras=2.13.1
* numpy=1.24.3
* pandas=2.0.3
* scikit-image=0.21.0
* matplotlib=3.7.2

## Conclusion

* The dataset is preprocessed and normalized and resized to 120x120 size.
* The model with 5 sets of Conv3D layers, 5 dense layers with a batch size of 30, running for 20 epochs.

## Contact

Created by [@omkar455] - feel free to contact us!
