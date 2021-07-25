## Predicting 3D anthropometric measurements
- A neural network model is designed to predict 3D anthropometric measurements from height, weight, gender and body shape from ANSUR-II dataset.
- The model predicts 13 anthropometric measurements as follows:
    Sleeves Length, Shoulder Width, Chest Around, Neck, Torso Length, Bicep Around, 
    Leg Length, Waist, Hips, Thigh, Rise, Wrist, Breast point
    
**Results:** 
- After training the model, mean squared error on test dataset is 836.26 and mean absolute error 
on test dataset is 21.14. 
- The below figure shows plots of mean squared error Vs epochs and mean absolute error Vs epochs.
![image](https://user-images.githubusercontent.com/58392171/126812122-f25797a5-8406-4bdd-9dc5-f2cfb6ad21b6.png)
- The below figure shows prediction Vs ground truth plots of each 3D anthropometric measurement on male 
and female test datasets separately. Note that plots of some measurements shows only for one 
gender because it is not required for other gender(according to task description).

![image](https://user-images.githubusercontent.com/58392171/126898963-7f775e78-de35-4877-9e60-77752529fb7c.png)



