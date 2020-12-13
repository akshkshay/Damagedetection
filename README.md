# Damagedetection
Problem Statement: Classifying buildings Post Hurricane using Satellite Imagery

The latest hurricane - Hurricane Iota, had 61 total fatalities, and 41 are still missing. After a hurricane, damage assessment is vital to the relief helpers and first responders so that resources and help can be planned and allocated appropriately. One way to measure the damage is to detect and quantify the number of damaged buildings, usually done by driving around the affected area and noting down manually. This process can be labor-intensive and time-consuming and not the most efficient method as well. Hence in this project, we will classify buildings between damaged and not damaged buildings using the satellite imagery. 

The data has the following subfolders:

train_another: the training data; 5000 images of each class(damage/no damage)

validation_another: the validation data; 1000 images of each class(damage/no damage)

test_another: the unbalanced test data; 8000/1000 images of damaged/undamaged classes

test: the balanced test data; 1000 images of each class(damage/no damage)

Solution Approach:
* Given image data we need to clean them and reshape the size for optimal computation.
* We have used  CNN to create  model and also experimented with diferent hyperparameters, optimizers and looked at how network is learning.
* Having different SOTA models and with clean data we have created model which actually provided ~98% accuracy on test dataset(balanced and unbalanced).

 ![Poster](image.jpeg)
 
Google colab link: https://colab.research.google.com/drive/1vjdGUrcg7o2xY2tkyyBoUZsI6z1LGD6w

Poster link: https://drive.google.com/file/d/1rJO5vTbaT3b58qxqWwrVO2lLg_mJcICc/view?usp=sharing

Short presentation recording: https://drive.google.com/file/d/1FekHrWermXM8hhBBnjuCIjjx8cImkskF/view

PPT Link: https://drive.google.com/file/d/1rTgxTP-Bureoaf9vqjs0Q3Tx_uEfpoKc/view?usp=sharing
