# Heart Sound Analysis using Machine Learning
----
* Understand Mel Frequency Cepstral Coefficents (MFCCs)
* Understand k-Nearest Neighbors (kNN) algorithm
* Understand Convolutional Neural Network (ConvNet/CNN)
* Classify abnormal/normal heart sound using MFCCs, kNN, CNN

## Dataset
----
Dataset is retrieved from the training set of [2016 PhysioNet/CinC Challenge](https://physionet.org/pn3/challenge/2016/ "Dataset"). There are 3,240 heart sounds colected in uncontrolled environment, saved in .wav format, each lasts from 5s to 120s. 

| Database | Abnormal | Normal | Total |
| --- | --- | --- | --- |
| Training-a | 292 | 117 | 409 |
| Training-b | 104 | 386 | 490 |
| Training-c | 104 | 7 | 31 |
| Training-d | 28 | 27 | 55 |
| Training-e | 183 | 1958 | 2141 |
| Total | 665 | 2575 | 3240 |

Table: Summary of dataset

## Libraries
---
Implementation is in Python3.
* [Librosa](http://librosa.github.io/ "Librosa") for reading and extracting MFCCs
* [sklearn](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html "kNN") for kNN
* [Keras](https://keras.io/ "Keras") for CNN

## Documents
This project includes:
   1. 01 [report](./report.pdf)
   2. 01 [notebook](./all-analysis.ipynb)
