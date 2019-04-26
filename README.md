# FGVCx Cassava disease diagnosis
![](cassava-banner.png)
This is a new Fine Grained Visual Categorization-x (FGVCx) challenge for 2019 that will run as part of the [FGVC6 workshop](http://fgvc.org) at [CVPR](http://cvpr2019.thecvf.com/)

## The Challenge
The goal of this task is to build a robust model that is able to distinguish between diseases in the Cassava plant. Cassava is an important food security crop for Africa grown by many small-holder farmers. The 4 diseases can be identified from the leaves of the plants. A possible extension of this challenge is to categorize the different severity levels of the diseases. 
![](cassava-leaf-imgs.png)

The key task with this dataset is to attempt a 5 class classification problem where you are attempting to distinguish between the 5 broad types of diseases; Cassava Mosaic Disease (CMD), Cassava Green Mite disease (CGM), Cassava Bacterial Blight (CBB), Cassava Brown Streak Disease (CBSD) and the health class (Figure above). In short, given a cassava leaf image can you predict the disease incidence.

A secondary task (to run after this challenge) would be to build a model that simultaneously predicts the disease incidence and severity. The data is labelled with the disease incidence and for each disease, the different types of example images of 5 types of severity scored 1-5; 1 being the class of a healthy leaf image, 5 being the class of a severely infected cassava plant as shown in the figure above.

## Kaggle
For this challenge, we are using Kaggle to host the data and the leaderboard. Checkout the competition page here.

## Dates (TBD)
|||
|----|---------------|
Data Released| 26-April-2019|
Submission Server Open | 26-April-2019|
Submission Deadline|  1-June-2019|
Winners Announced| June 2019|

## Data
The data will consist of leaf images in each class. An abstracted reduced dataset of the images can be [downloaded here](pdata.zip).

