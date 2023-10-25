# Project Name
> House Price prediction using advanced regression


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. 
  They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing 
  dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- After comparing both the Ridge and Lasso regularization models we can see that the below features are best explaining the Dataset (combining Ridge & Lasso):
**OverallCond_3: Overall quality condition being Fair. (Negatively correlated)**

**OverallQual_9: Overall quality being Excellent. (Positively correlated)**

**Neighborhood_Crawfor: Physical location Crawford. (Positively correlated)**

**OverallCond_4: Overall quality condition Below Average. (Negatively correlated)**

**PoolQC_Gd: Good Pool Quality. (Negatively correlated)**

**Functional_Typ: Typical Functionality. (Positively correlated)**

**CentralAir_Y: Central air conditioning needed. (Positively correlated)**

Optimal alpha value for Ridge: 10.21.
Optimal alpha value for Lasso: 0.001.

**Since we have too many preditor variables, we would use Lasso Regression as reduces the coefficients of predictor variables to 0 there by doing an automatic feature selection.**

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy & Pandas
- Seaborn
- Sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@krissravi36] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->