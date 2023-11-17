# Pneumonia-Diagonose
# Classifying Pneumonial Chest X-ray using a CNN

<pre>


Author           : Meijuan Xia
Project Name     : Classifying Pneumonial Chest X-ray using a CNN
                   
Description      : 1. Analysed data and classified pneumonial from Chest X-Ray images using Custom Deep Convololutional Neural Network with 5856 images 
                   2. Analysed the impact of the parameters and counts of training and validation data on performence
                   3. With Deep Convololutional Neural Network attained testing accuracy 93.47% and loss 0.20.

Dataset Link:     https://www.kaggle.com/datasets/lasaljaywardena/pneumonia-chest-x-ray-dataset



</pre>

## Introduction of the dataset



The chest X-ray images were selected from retrospective cohorts of pediatric patients aged one to five years old. All chest X-ray imaging was performed as part of the patients' routine clinical care.

For the analysis of chest x-ray images, all chest radiographs were initially screened for quality control by removing all low-quality or unreadable scans. The diagnoses for the images were then graded by two expert physicians before being cleared for training the AI system. 

The dataset is organized into 3 folders: train, test and val. Each folder contains subfolders for each image category, namely Pneumonia and Normal. The dataset comprises 5,863 X-Ray images (JPEG format) across two categories (Pneumonia/Normal).


## Process of the training and testing result

- Load the data
- Analyse the raw data,  
- Build the models
- Train the models
- Evaluate the models
- Change the parameters and compare the performance

## Detail performance report
<pre>
------------------------------------
Loss     : 0.20  
Accuracy : 93.47%
--------------------------------------------------------------------------------
Precision    :  92.26 % 
Recall    :  98.92 % 
F1-Score    :  95.47 % 
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
              precision    recall  f1-score   support

      normal       0.97      0.81      0.88       121
   pneumonia       0.92      0.99      0.95       277

    accuracy                           0.93       398
   macro avg       0.95      0.90      0.92       398
weighted avg       0.94      0.93      0.93       398

--------------------------------------------------------------------------------
</pre>
