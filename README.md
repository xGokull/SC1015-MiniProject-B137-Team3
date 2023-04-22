# SC1015-MiniProject-B137-Team3
## Research Question:
What is the relationship between personality factors and the likelihood that the person consumes Methamphetamine, Heroin, and Cannabis?

## Introduction:
This project aims to explore the relationship between personality factors and the consumption of three most abused drugs in Singapore; Methamphetamine, Heroin, and Cannabis.

## Cleaning the Data:
The dataset used in this project was cleaned to remove a fake drug included in the dataset to filter out non-serious respondents. Additionally, a few classes were clubbed in variables to decrease class imbalance.

## Exploratory Data Analysis (EDA):
EDA was conducted by plotting the use of the three drugs against all personality types. Chi-squared analysis was used to find associations among all variables concerned.

# Models Used:

## Random Forest Classifier:
Random Forest Classifier was used to predict drug consumption, but the accuracy was not satisfactory due to class imbalance. Techniques such as k-shuffle and shuffle split were used to improve accuracy, but it didn't show significant improvement, and the accuracy remained at 47%.

## SVC:
SVC was used, and it showed good accuracy. The model always predicted "Not a user" for all data initially, but L2 regularisation was used to counter that, which resulted in an accuracy of around 80%. Principal Component Analysis (PCA) was used to visualise the results.

## Neural Network:
A neural network was constructed with two hidden layers of six and four nodes, respectively. This model showed a high accuracy of 93%.

## Conclusion:
This project explored the relationship between personality factors and drug consumption using three different models. SVC and Neural Network showed promising results. However, due to the nature of drug consumption data, the models' accuracy was affected by class imbalance. Nonetheless, the results obtained from this project could be used to further investigate the relationship between personality factors and drug consumption.

## Contributions:
1. Data Cleaning: Luo Maoyuan
2. EDA: Luo Maoyuan and Gupta Raghav
3. Random Forest Classifier: Gokul Ramesh 
4. SVC: Gokul Ramesh and Gupta Raghav
5. Neural Network: Gupta Raghav

## References:
1. Database: https://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29
2. https://github.com/deepak525/Drug-Consumption/blob/master/drug.ipynb
3. https://faroit.com/keras-docs/1.1.0/models/sequential/
4. https://www.cnb.gov.sg/docs/default-source/drug-situation-report-documents/cnb-annual-statistics-2021.pdf
