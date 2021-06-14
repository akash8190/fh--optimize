# fh--optimize

## About Project
![image](uploads/80e172c82465eb2943d69bb13fb05c83/image.png)

-  Predicting the  Best_day or Best_time for a marketing campaign. we have to predict the best day or best time to send a marketing campaign.

## Data Overview
- For completing this project we have a 4 file which is store in the s3 bucket on the AWS platform. 
1. Click_csv
2. sent_csv
3. open_csv

- we have to combine all three file into one file for data preprocessing
Other files are 
1. Demographic_csv
2. Shareholder_account_csv
3. SIP_regerstration_csv
![image](uploads/90608eabcab3a45cc17d18ce0f2fb833/image.png)
## Data understanding

- We have to analyze all the data and remove those feature which is not useful in our marketing campaign.

## Project Execution Step

- After analyzing the data we simply follow the life cycle of the Data Science project :
(![image](uploads/803c02ec4f2366822bd9fa57dfc9a471/image.png)

- data collection
- data cleaning
- Exploratory Data Analysis
- Feature Engineering
- Feature selection
- model building
- model hyperparameter Tunning
- model deployment

## Tools And Technology Used
- python
- AWS Sagemaker
- AWS S3 Bucket
- NumPy, pandas, sklearn
- Gitlab

## Model Building 

- For model building, we have to select the most important feature which is most relevant to predict the output and give the result some of the features are:
![image](uploads/b12349a9c452022ba3d7b37010a41060/image.png)

![image](uploads/840def75fae47e2700a1378ee4c69662/image.png)

- Now we have to train our model to predict the output and we try with different algorithms but the random forest algorithm gives the best accuracy.
