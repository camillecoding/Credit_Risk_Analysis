# Credit Risk Analysis
This project relies on a few methods of Machine Learning to determine which, if any, method exhibits the least amount of bias in determining customer credit risk.

## Analysis ##
Below I have analyzed the results of my project.

### Overview ###
It is important for lending institutions to examine the full profile of a potential borrower so that they can determine whether to lend, and if so, what a reasonable interest rate will be. There have been insidious cases where human or computer bias keeps some borrowers out of the market entirely and subjects others to unfairly high interest rates based on their demographics. My project aims to identify any machine learning biases so understand which method will provide the most accurate and fair results. I tested 6 machine learning models in this project. 

### Results ###

*Oversampling
* The oversampling method resulted in 99% precision and 71% sensitivity (recall).

<img width="747" alt="Screen Shot 2022-04-09 at 11 28 42 AM" src="https://user-images.githubusercontent.com/95657458/162580625-8e70abb5-1550-4812-861d-067a4bc9a152.png">

*SMOTE
* The SMOTE method in 99% precision and 74% sensitivity (recall).

<img width="709" alt="Screen Shot 2022-04-09 at 11 31 26 AM" src="https://user-images.githubusercontent.com/95657458/162580739-676352ce-0c37-45f9-8c42-6d7ff75f7fb2.png">

*Undersampling
* The undersampling method resulted in 99% precision and 55% sensitivity (recall).

<img width="717" alt="Screen Shot 2022-04-09 at 11 32 15 AM" src="https://user-images.githubusercontent.com/95657458/162580759-732d2e28-b48e-42dd-a7b6-e0a6bc468eef.png">

*SMOTEENN
* The SMOTE model resulted in 99% precision and 58% sensitivity (recall).

<img width="729" alt="Screen Shot 2022-04-09 at 11 32 46 AM" src="https://user-images.githubusercontent.com/95657458/162580778-79a48e53-83ae-4908-96be-6b7d4a6f4ffc.png">

*Balanced Random Forest Classifier
* The SMOTE model resulted in 99% precision and 88% sensitivity (recall).

<img width="723" alt="Screen Shot 2022-04-09 at 11 33 08 AM" src="https://user-images.githubusercontent.com/95657458/162580789-065545d4-1bbe-465a-bd9b-811e7ba1fbb3.png">

*Easy Ensemble Classifier
* The SMOTE model resulted in 99% precision and 94% sensitivity (recall).

<img width="733" alt="Screen Shot 2022-04-09 at 11 33 47 AM" src="https://user-images.githubusercontent.com/95657458/162580810-437e5f45-8188-4aa8-835b-5add9a2e109d.png">

### Summary ###
While precision is important, the sensitivity of the tests in crucial, as this metric can indicate whether the test is generating too many false positives and negatives. 

