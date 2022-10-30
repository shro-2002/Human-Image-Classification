# Human-Image-Classification
The strategy for the collection of data has been finalized and it was accomplished by using a web scraper built using Python language for the data scraping. The haar cascade classifier was used in order to identify the person's nationality on the basis of their skin color.
This repository contains a train, Human classification, test(Indian or non Indian verification) and main file and also the face haarcascade file used in the model.

train.py: Simply enter the path of the train folder and create two folders, Indian and Non-Indian, containing the relevant photos to train the model. In the same directory, simply run the train file. The train file creates three files: features.npy, labels.npy, and face trained (yml) file after extracting the photos from the respective directories. These three files save the image's features and make use of them during testing.
