# Fingers Detection and Counting using OpenCV and Python - Machine Learning Project


## Introduction
In this project, we have developed different models throughout different classification techniques that classifies the dataset based on the number of raised fingers, and which hand is used. Each image has a label assigned to it as we will see further below. Firstly, we processed the dataset so that every model uses the same dataset and the same properties, as a result, it can be compared fairly and equally. We have taken the dataset and convert it to a one-dimensional array. Then used StandardScaling to standardizes the features. We used Python to code our models and we used a dataset(fingers) made by 'koryakinp' which is on Kaggle.

----

#### Dataset description
21600 images of left and right hands fingers.

----

#### Images specification
- All images are 128 by 128 pixels.
- Training set: 18000 images.
- Test set: 3600 images.
- Images are centered by the center of mass.
- Noise pattern on the background.

----
#### Labels
Labels are in 2 last characters of a file name. L/R indicates left/right hand; 0,1,2,3,4,5 indicates number of fingers.

The dataset is available on kaggle.
Dataset url: https://www.kaggle.com/koryakinp/fingers
