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


### Easy Ensemble Classifier



## Summary

