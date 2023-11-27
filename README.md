# ASL_Classification
Trained Models on Letters/Images Dataset

ASL Classification: A machine learning project for American Sign Language (ASL) classification using computer vision and hand landmark detection. 

## Overview
- **dataset_preview** : This folder basically gives you a glance on how the dataset would look like. The original dataset was taken from kaggle here. I removed a few images as they were blur and were too dark to ensure the accurate hand landmark detection. The dataset I used to train is here.

- **hand_landmarker.task** : There is a line of code in the notebook which downloads this file which is necessary to run the code for hand landmark detection. This file can simply be placed in the PythonI folder -> Lib folder -> site-packages folder. The path for me was D:/Software/PythonI/Lib/site-packages/

- **hand_landmarks.png** : This image will better give you an understanding of landmarks on a hand which I used to calculate angles between two lines. The landmark numbers used in the code can be referenced from here. 

- **ASL_Classification.ipynb** : This notebook contains the full code to train multiple classifiers and choose the best classifier which can be used to predict custom videos. Pre-requsite for the code to work is to download the dataset and place it inside this ASL_Classification folder or in the same directory as the notebook. 


## Run Locally

1. Download the zip file, or clone the repository. 

``` 
# Clone the repository
git clone https://github.com/HibbanHaroon/ASL_Classification.git
```

2. Download the dataset from either kaggle or from here (Some images were removed for clarity from the dataset uploaded on google drive).

3. Place the hand_landmarker.task inside PythonI folder -> Lib folder -> site-packages folder. 

3. Simply run the notebook. 
