# Attrition with Branched Neural Network

## Overview
The objective of this model is to predict whether employees are likely to leave the company.  This information could be utilized by HR department of this fictional company.  In addition, the model will predict which department an emploee is best suited for.  

## Model
The selected model uses a branched neural network to make its predictions using the following libraries:
![Screenshot 2024-08-01 154028](https://github.com/user-attachments/assets/334deea1-5937-4f50-abb9-892c77ab198d)

Data was obtained from the following site:
 [https://static.bc-edx.com/ai/ail-v-1-0/m19/lms/datasets/attrition.csv](https://)


## Summary
Here is a summary of the test results of the model.  Answers to below questions are provided below.

**1. Is accuracy the best metric to use on this data? Why or why not?**
   
*Maybe accuracy is not the best to use on this data.  The model predicted 
attrition somewhat accurately while it predicted department correctly only
half the time.*

**2. What activation functions did you choose for your output layers, and why?**
   
*I chose Softmax for department because of the multiple values for its 
classification.  For attrition, I chose Softmax because it is a binary
classification (Yes/No).*

**3. Can you name a few ways that this model might be improved?**
   
*This model could be improved by training with more data, adding more layers
to the model or changing the parameters of the model.*

