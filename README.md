# Housing Sale Prediction Case Study
> A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company wants to know:
1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.
- We need to build a model and regularize it to make it more robust and generalizable

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Total Basement Square Feet Area(TotalBsmtSF), as this increases the SalePrice of house increases.
- Above grade (ground) living area square feet(GrLivArea), as this increases SalePrice of house increases
- Excellent OverallQual(OverallQual_10) increases the SalePrice of the house
- Duplex houses(MSSubClass_90), these lead to lesser SalePrice.
- Typical or average(KitchenQual_TA) leads to lower SalePrice
- Below Average or Fair condition of the house(OverallCond_3), leads to lower SalePrice
- Typical Basement Quality(BsmtQual_TA) leads to lower SalePrice
- 2nd Floor Sqaure Feet Area(2ndFlrSF), as this increases SalePrice increases, beacuse people tend to like higher floor for better view and more floors in a house means more space that can be rented out, and as area of 2ndFloor increases this increases SalePrice.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook(Anaconda 3) - version 6.4.8
- Python3 - version 3.10
- numpy - version 1.21.5
- pandas - version 1.4.2
- matplotlib - version 3.5.1
- seaborn - version 0.11.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was inspired by UpGrad Advanced Regression course
- References - google.com, quora.com, stackoverflow.com


## Contact
Created by zuhu2195 - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
