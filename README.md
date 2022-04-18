# Credit_Risk_Analysis

## OVERVIEW
At LendingClub, the higher managemnet believes that we should use Machine Learning to help prevent credit risk. They believe it will provide a quicker and more liable experience and addidtionally it will be more accurate that will lower default rates. Today I am helping the Jill, Lead Data Scientist to implement the plan. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will need to employ different techniques to train and evaluate models with unbalanced classes. I have also used imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

In my analysis you will find below; I've built the six machine learning models and algorithems to predict credit risk. In my results I've added their balanced accurancy scores, the precision and recall scores. Once the results are complete it will be more visual to evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


## RESULT
### Deliverable 1: USED RANDOM OVER SAMPLER, SMOTE AND CLUSTER CENTROIDS 
- RANDOM OVER SAMPLER

Balanced Accurancy Score: 65.4%

Precision: 99%

Recall: 59%

<img width="442" alt="Screenshot 2022-04-18 at 5 47 17 PM" src="https://user-images.githubusercontent.com/95388367/163883081-c6c9c96f-e22e-465f-8423-7b20a62bf848.png">

<img width="685" alt="Screenshot 2022-04-18 at 5 47 22 PM" src="https://user-images.githubusercontent.com/95388367/163883110-503a82bf-d9ac-40c2-b1f0-dd3f8c92ed9d.png">


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

## SUMMARY 
In summary, I would not recommend to use the SMOOTEEN method due to a Balanced accuracy score of 58.1%. Also from the six I would recommend to use the 
Easy Ensemble Classifier due to the percentages being more high which will conclude accuracy.

