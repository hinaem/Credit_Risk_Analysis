# Credit_Risk_Analysis

## OVERVIEW
At FAST LENDING SERVICES USE MACHINE LEARNING TO PREVENT CREDIT RISK. MANAGMENT BELIEVES THIS WILL PROVIDE A QUICKER AND MORE LIABLE EXPERIENCE. ALSO MORE ACCURATE RESULTS THAT WILL LOWER DEFAULT RATES. Today I am helping the Lead Data Scientist to implement the plan. 

In my analysis you will find below; I've built the six machine learning models and algorithems to predict credit risk. In my results I've added their balanced accurancy scores, the precision and recall scores.

Precision is the measure of how reliable a positive classification is. 
Recall is the ability of the classifier to find all the positive samples.

## RESULT
### Deliverable 1: USED RANDOM OVER SAMPLER, SMOTE AND CLUSTER CENTROIDS 
- RANDOM OVER SAMPLER



- SMOTE 

Balanced Accurancy Score: 66.2%

Precision: 99%

Recall: 69%


![SMOTE BAC](https://user-images.githubusercontent.com/95388367/163750253-c77499da-4742-4ad0-9765-b84c3923013b.png)


![SMOTE RS](https://user-images.githubusercontent.com/95388367/163750267-478653cb-b944-4313-9ba0-c7bb3df316b2.png)

- CLUSTER CENTROIDS

Balanced Accurancy Score: 66.2%

Precision: 99%

Recall: 55%


![CLUSTER BAC](https://user-images.githubusercontent.com/95388367/163750302-93d10f2d-d227-4c28-ac2c-d0e381e5f4e4.png)

![CLUSTER RS](https://user-images.githubusercontent.com/95388367/163750319-41ffad03-6673-40d0-a056-1e036d8377d7.png)


### Deliverable 2: USED SMOOTEEN 
- SMOOTEEN 

Balanced Accurancy Score: 58.1%

Precision: 99%

Recall: 69%


![SMOTEENN BAC](https://user-images.githubusercontent.com/95388367/163750346-be911087-9420-4656-acdd-4d05aa278bd4.png)

![SMOTE RS](https://user-images.githubusercontent.com/95388367/163750354-ef037bf5-371f-424a-80c8-8a47c5b703c3.png)


### Deliverable 3: USED BALANCED RANDOM FOREST CLASSIFER AND EASY ENSEMBLE CLASSIFER 
- BALANCED RANDOM FOREST CLASSIFER

Balanced Accurancy Score: 78.7%

Precision: 99%

Recall: 91%


![FOREST BAC](https://user-images.githubusercontent.com/95388367/163750378-d736daae-4d4f-4447-a600-9899d880d98b.png)

![FOREST RS](https://user-images.githubusercontent.com/95388367/163750386-61ed2c6c-cbc5-4567-a940-2b4ce2038e24.png)


- EASY ENSEMBLE CLASSIFIER 

Balanced Accurancy Score: 92.5%

Precision: 99%

Recall: 94%


![EASY BAC](https://user-images.githubusercontent.com/95388367/163750398-5b1e7fea-c670-4cf4-b543-fc0260805679.png)

![EASY RS](https://user-images.githubusercontent.com/95388367/163750412-d4f74dbb-535f-4d62-b2b4-aee55e05604b.png)

Let's go over the results in the classification report:


In summary, this model may not be the best one for preventing fraudulent loan applications because the model's accuracy, 0.552, is low, and the precision and recall are not good enough to state that the model will be good at classifying fraudulent loan applications. Modeling is an iterative process: you may need more data, more cleaning, another model parameter, or a different model. It's also important to have a goal that's been agreed upon, so that you know when the model is good enough.
## SUMMARY 

