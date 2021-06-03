# CMPE255Team5
***CMPE 255 - Data Mining Spring 2021 Group Project, Team #5
Sajit Jumani & Nelson Paz***

***CODE Evaluation***

1) Download and Upload "TEAM5 - Daily And Sports Activities Prediction - PROFESSOR Version.ipynb" onto a Jupiter Notebook directory. 
 
2) Add the following files to the same directory:
   -  X_train_p.txt
   -  y_train_p.txt
   -  X_test_p.txt
   -  y_test_p.txt
3) Left Click on Kernel. & then "Restart and Run All". 

The Code will import the necessary Libraries and then perform two types of Classification: 

  - _First:_ **Artificial Neural Network Model**: 3 Types (two, three and four layers)

  - _Second:_ **Random Forest Classifier**. 

Each Model would train with the provided subset of original data set. 
After training is completed the model will perform a test run with the remaining data and Output a Score of Accuracy and Loss. 
Each Model would output a graph for the confusion Matrix visualization. 

For more Information about the Data Preprocessing please reffer to: 
"TEAM5 - Daily And Sports Activities Prediction - STUDENT Version.ipynb" or "pdf version"
Original Data set is not attached or linked to the code. 

**About the Original Data:** 

Dataset used for this project is from UCI Machine Learning Repository

The raw dataset has outputs from 8 people doing 19 different activities for 5 minutes each.
The data gathered was from 9 sensors per location (5 locations total), for a total of 45 sensor 
axes at a frequency of 25Hz. Each 5 minute dataset was broken up into 480 5-second 
segments. Therefore there are 45 attributes and 125 rows per 5-second file for each of the 8 
individuals and for each of the 19 activities. 

https://archive.ics.uci.edu/ml/datasets/daily+and+sports+activities
Source:
Billur Barshan,
Department of Electrical and Electronics Engineering, Bilkent University, TR-06800 Bilkent, Ankara, Turkey
