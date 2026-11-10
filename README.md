# House Price Prediction
> Model the price of houses with the available independent variables.


## Table of Contents
* [General Info](#general-information)
* [How to Run](#how-to-run)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.
- The company wants to know:
    Which variables are significant in predicting the price of a house, and
    How well those variables describe the price of a house.
  Also, determine the optimal value of lambda for ridge and lasso regression.  
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- Dataset being used - https://ml-course3-upgrad.s3.amazonaws.com/Assignment_+Advanced+Regression/train.csv

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- The most important predictor variables are GrLivArea, OverallQual, BsmtFinSF1, GarageArea, TotalBsmtSF.
- The optimal value of alpha for ridge regression is 500 and lasso regression is 1000.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## How to run
1. Install the libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn
   ```
2. Get the data: [train.csv](https://ml-course3-upgrad.s3.amazonaws.com/Assignment_+Advanced+Regression/train.csv) (place it next to the notebook).
3. Open and run the notebook:
   ```bash
   jupyter notebook "House_Price_Prediction.ipynb"
   ```

## Technologies Used
- Jupyter Notebook
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
