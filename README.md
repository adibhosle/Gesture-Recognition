# Gesture-Recognition

Imagine you are working as a data scientist at a home electronics company which manufactures state of the art smart televisions. You want to develop a cool feature in the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.



## Table of Contents
* General Info
* Technologies Used
* Conclusions
* Acknowledgements



## General Information
The training data consists of a few hundred videos categorised into one of the five classes. Each video (typically 2-3 seconds long) is divided into a sequence of 30 frames(images). These videos have been recorded by various people performing one of the five gestures in front of a webcam - similar to what the smart TV will use. 

You can download the dataset [here](https://drive.google.com/uc?id=1ehyrYBQ5rbQQe6yL4XbLWe3FMvuVUGiL).

The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:

- Thumbs up:  Increase the volume
- Thumbs down: Decrease the volume
- Left swipe: 'Jump' backwards 10 seconds
- Right swipe: 'Jump' forward 10 seconds  
- Stop: Pause the movie
 
Each video is a sequence of 30 frames (or images).



## Technologies Used
- Python Libraries for visualising, training & Testing model. Such as - numpy, pandas , statsmodel, sklearn, seaborn & matplotlib.
- Jupyter Notebook
- Tensorflow
- Github



## Conclusions
After creating 11 model with different parameters and methods combination we achieved good accuracy. Details are in the notebook.



## Acknowledgements
- Upgrade Learning
- Upgrade Faculty
- Aditya Bhosle


## Contact
Created by [Aditya Bhosle](https://github.com/adibhosle) - feel free to contact me!
