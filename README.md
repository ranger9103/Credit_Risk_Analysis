# Credit_Risk_Analysis

## Analysis

Credit risk analysis is not a balanced situation. There are very few bad loans compared to the number of good loans. In order to fully evaluate and predict accurate credit risk, imbalanced-learn and scikit-learn to evaluate. 

## Results
### Random Over Sampling Method

The balanced accuracy is 63%. 
There is a high level of precision for low-risk at 100% and a very low level of precision with high_risk with 0.01%.
Sensitivity is 58% and 68% for high and low risk respectively. 

![image](https://user-images.githubusercontent.com/101893338/179433525-c88ee07f-5cc4-4ffc-aba1-b9b8db321afe.png)
![image](https://user-images.githubusercontent.com/101893338/179433434-06fea6ea-65e9-4b10-8d9c-80a2c9066cb9.png)
![image](https://user-images.githubusercontent.com/101893338/179433458-836005c6-c285-494d-a69d-124dbe4e3b3c.png)

### SMOTE Method

This model output is almost identical to the random oversampling method
The balanced accuracy is 63%. 
There is a high level of precision for low-risk at 100% and a very low level of precision with high_risk with 0.01%.
Sensitivity is 57% and 68% for high and low risk respectively. 

![image](https://user-images.githubusercontent.com/101893338/179434397-4662b938-8f00-4464-ba24-1b3f4c023b83.png)
![image](https://user-images.githubusercontent.com/101893338/179433783-64ea5216-6fd8-4e8b-9d77-227f70efbfa5.png)

### Cluster Centroids Method

With Cluster Centroids we continue to see very similar output.
The balanced accuracy is 63%. 
There is a high level of precision for low-risk at 100% and a very low level of precision with high_risk with 0.01%.
Sensitivity is 57% and 68% for high and low risk respectively.

![image](https://user-images.githubusercontent.com/101893338/179433832-a480fa5b-6f5d-4189-97a7-94a6e8e86b79.png)
![image](https://user-images.githubusercontent.com/101893338/179434581-d2f5af63-b11b-4c8d-9667-44620fe9d6c2.png)

### SMOTEENN Method

The balanced accuracy is 62%. 
There is a high level of precision for low-risk at 100% and a very low level of precision with high_risk with 0.01%.
Sensitivity is 70% and 54% for high and low risk respectively.

![image](https://user-images.githubusercontent.com/101893338/179434814-ca38aa4b-e6e4-4bd9-a927-30d365839571.png)
![image](https://user-images.githubusercontent.com/101893338/179434828-afe82d77-7bf5-45c8-8340-3300991c9882.png)

### Balanced Random Forest Classifier

The balanced accuracy is 79%. 
There is a high level of precision for low-risk at 100% and a very low level of precision with high_risk with 0.04%.
Sensitivity is 67% and 91% for high and low risk respectively.

![image](https://user-images.githubusercontent.com/101893338/179434955-b0e8af6e-e9fc-42e0-8571-28ba017ec1be.png)
![image](https://user-images.githubusercontent.com/101893338/179434968-ac07ffac-ad78-427f-ac2c-a6448239adb6.png)

### Easy Ensemble Classifier

The balanced accuracy is 93%. 
There is a high level of precision for low-risk at 100% and a very low level of precision with high_risk with 0.07%.
Sensitivity is 91% and 94% for high and low risk respectively.

![image](https://user-images.githubusercontent.com/101893338/179435069-70544dfe-82d5-4488-8807-409ecbe4155a.png)
![image](https://user-images.githubusercontent.com/101893338/179435088-72666179-963a-4348-a169-a5b67a5afb2b.png)

## Summary

The easy ensemble classifier has the highest accuracy with high sensitivity as well. Balanced random forest classifier is the next best with accuracy of 79%. The rest of the models are 62-63% balanced accuracy with varrying sensitivities. 
For these reasons, easy ensemble classifier would be the model I would recommend.
