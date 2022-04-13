# Handwritten-Character-Recognition
Deep Learning Model for character recognition.

[![Ask Me Anything !](https://img.shields.io/badge/ask%20me-linkedin-1abc9c.svg)](https://www.linkedin.com/in/arnav-modanwal-b4b111188)

### Dataset: [A-Z Handwritten Alphabets in .csv format](https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format)

## Overview
This repository contains all the codes and reference data for building the Handwritten Character recognition Model from scratch.

### Abstract
A Deep Learning Model for handwritten character recognition (A-Z).
The Dataset containg 26 folders from A to Z containing handwritten images in size 28*28 pixels, each alphabet in the image is centre fitted. Each Image is stored as Gray-level.
The feature extraction technique is obtained by normalizing the pixel values. Pixel values will range from 0 to 255 which represents the intensity of each pixel in the image and they are normalized to represent value between 0 and 1. Convolutional neural network is used as a classifier which trains the [kaggle](https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format) dataset. The prediction for the given input image is obtained from the trained classifier.

data.info()
```
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 372450 entries, 0 to 372449
Columns: 785 entries, 0 to 0.648
dtypes: int64(785)
memory usage: 2.2 GB
```

data.shape()
```
(372450, 785)
```
## Packages used
- [Tensorflow](https://www.tensorflow.org/)
- [Scikit-learn](http://scikit-learn.org)
- [OpenCV](https://opencv.org/)
- [Numpy](http://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

### All Files
1. (A-Z) Images : Contains the Handwritten images written by me;
2. best_model.h5 : Deep Learning Model;
3. Character recoginition.ipynb : Code for building the model from scratch;
4. Hand Written character Recognition.ipynb : contains the code for recogizing the handwritten characters written by me.

## Screenshots/Images

### Random Images From the Dataset

![Screenshot 2022-04-12 230514](https://user-images.githubusercontent.com/74757456/163021880-014d623b-9fbe-484e-b794-c4646e7d56a0.png)

### Making Prediction On Test Dataset
![Screenshot 2022-04-12 231418](https://user-images.githubusercontent.com/74757456/163022592-0661ab1f-d8cb-4a44-a38d-1621429506fe.png)

### Handwritten Alphabets written by me

![Screenshot 2022-04-12 231712](https://user-images.githubusercontent.com/74757456/163023056-a820aba6-4f69-48e1-b184-bd38c224dbd9.png)

### Making Predictions on the Handwritten Characters
![Screenshot 2022-04-12 231922](https://user-images.githubusercontent.com/74757456/163023363-8a39f222-9ea4-4fbd-bf71-389548fe1f70.png)

### Further Improvement
* Real Time Character Recognition
* Better Image Processing such as: reduce background noise to handle real time image or images in different lighting conditions more accurately.

Feel Free to suggest an improvemet in this project.

This is a work from my 4th semester in Computer Enginnering from Saffrony Institute of Technology. Also I was assigned this project work from the Nano Degree course of [Autonomous Vehicles](https://www.elitetechnogroups.com/internship/best-course-for-autonomous-vehicle-using-advanced-ml-ai-iot.php) by [Elite Techno Groups](https://www.elitetechnogroups.com/) in April 2022.
