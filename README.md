# Machine Learning to detect people's emotions

A repository for Group 2

## Project Proposal

### Team Members

* Name: **Allison Wells**
* Name: **William Brown**
* Name: **Chris Winn**
* Name: **William Brown**
* Name: **Syed Husain**

### Project Description

In this project, we will be analyzing human emotions at a live performance:
* Live performance
* Sports Event
* Political Debate

## Data:
Grayscale portraits of faces measuring 48 × 48 pixels make up the data. The faces have been automatically registered so that each face roughly fills the same amount of space in each image and is roughly centered. The aim is to classify each face into one of seven categories based on the emotion displayed in the facial expression (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

"Emotion" and "Pixels" are two columns in train.csv. The emotion that is present in the image is represented by a numeric code in the "emotion" column that ranges from 0 to 6, inclusive. For each image, a string enclosed in quotes is present in the "pixels" column. The values in this string are separated by spaces and are arranged in row major order. The "pixels" column is the only one in test.csv.

Data source: https://huggingface.co/spaces/mxz/emtion/blob/c697775e0adc35a9cec32bd4d3484b5f5a263748/fer2013.csv
