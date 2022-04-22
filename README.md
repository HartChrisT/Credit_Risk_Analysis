# Credit_Risk_Analysis

## Overview of Analysis

Purpose: To help Fast Lending better identify low-risk loan candidates by evaluating various machine learning models and sampling algorithms to help lower default rates and increase profits.

## Results
![naive_random_oversampling_1](https://user-images.githubusercontent.com/92996865/164578155-b7ced05e-8da4-4f7b-9450-4f52dfcac0a4.png)

- The balanced accuracy score indicates that 83.2% of the Naive Random Oversampling model's predictions were correct overall.
- High risk loans had a precision of 3%, meaning of the samples the model predicted as high risk, 3% of them were actually high risk.
- High risk loans had a recall of 82%, meaning the model accurately identified 82% of the high risk loans.
- Low risk loans had a precision close to 100%, and a recall of 84%, or falsely identifying 16% of low risk loans as high risk.

![SMOTE_Oversampling_2](https://user-images.githubusercontent.com/92996865/164578167-c25f30b8-4c52-4420-9f50-a9190c24c304.png)

- The balanced accuracy score indicates that 83.8% of the SMOTE Oversampling model's predictions were correct overall.
- High risk loans had a precision of 3%, meaning of the samples the model predicted as high risk, 3% of them were actually high risk.
- High risk loans had a recall of 81%, meaning the model accurately identified 81% of the high risk loans.
- Low risk loans had a precision close to 100%, and a recall of 87%, or falsely identifying 13% of low risk loans as high risk.

![Undersampling_3](https://user-images.githubusercontent.com/92996865/164578177-05a0a5bc-39b3-450a-bfe9-5fff4afee7e0.png)

- The balanced accuracy score indicates that 81.2% of the Undersampling model's predictions were correct overall.
- High risk loans had a precision of 2%, meaning of the samples the model predicted as high risk, 2% of them were actually high risk.
- High risk loans had a recall of 86%, meaning the model accurately identified 86% of the high risk loans.
- Low risk loans had a precision close to 100%, and a recall of 76%, or falsely identifying 24% of low risk loans as high risk.

![SMOTTEN_combosamp_4](https://user-images.githubusercontent.com/92996865/164578187-ffc64646-8196-439b-b139-925dbde88094.png)

- The balanced accuracy score indicates that 83.8% of the SMOTTEN (Over & Under) Sampling model's predictions were correct overall.
- High risk loans had a precision of 3%, meaning of the samples the model predicted as high risk, 3% of them were actually high risk.
- High risk loans had a recall of 82%, meaning the model accurately identified 82% of the high risk loans.
- Low risk loans had a precision close to 100%, and a recall of 86%, or falsely identifying 14% of low risk loans as high risk.

![Balanced_Random_Forest_Classifier_5](https://user-images.githubusercontent.com/92996865/164578196-608cfa54-77ab-4c13-ab9f-84de4edffc4a.png)

- The balanced accuracy score indicates that 78.8% of the Balanced Random Forest Classifier model's predictions were correct overall.
- High risk loans had a precision of 3%, meaning of the samples the model predicted as high risk, 3% of them were actually high risk.
- High risk loans had a recall of 70%, meaning the model accurately identified 70% of the high risk loans.
- Low risk loans had a precision close to 100%, and a recall of 87%, or falsely identifying 13% of low risk loans as high risk.

![Easy_Ensemble_AdaBoost_Classifier_6](https://user-images.githubusercontent.com/92996865/164578208-4e14f673-f51c-4a05-8d68-c5c0e95660c4.png)

- The balanced accuracy score indicates that 93.2% of the Easy Ensemble Classifier model's predictions were correct overall.
- High risk loans had a precision of 9%, meaning of the samples the model predicted as high risk, 9% of them were actually high risk.
- High risk loans had a recall of 92%, meaning the model accurately identified 92% of the high risk loans.
- Low risk loans had a precision close to 100%, and a recall of 94%, or falsely identifying 6% of low risk loans as high risk.

## Summary

I recommend using the Easy Ensemble Classifier model based of the raw results alone. The recall rate for high risk loans is an astounding 92%, and arguably most important stat for the company because falsely identifying high risk loans will cost the company money. The recall rate of 9% is the highest by far, which means the comany is losing out on less potential profits using this model as opposed to the others because it is falsely identifying less low risk loans as high risk.   
