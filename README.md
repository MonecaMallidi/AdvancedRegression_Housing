# AdvancedRegression_Housing

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
## Table of Contents


- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)


## Conclusions

 Though the model performance by Ridge Regression was better in terms of R2 values of Train and Test, It is better to use Lasso, since it brings and assigns a zero value to insignificant features, enabling us to choosethe predictive variables.
It is always advisable to use simple yet robust model.
The higher values of positive coeeficients suggest a high sale value.
Some of those features are:-

GrLivArea	Above grade (ground) living area square feet,
OverallQual	Rates the overall material and finish of the house,
OverallCond	Rates the overall condition of the house,
TotalBsmtSF	Total square feet of basement area,
GarageArea	Size of garage in square feet.

The higher values of negative coeeficients suggest a decrease in sale value.
Some of those features are:-
PropAge	Age of the property at the time of seeling,
MSSubClass	Identifies the type of dwelling involved in the sale.


## Technologies Used

- numpy - version 1.23.5
- pandas - version 1.5.3
- matplotlib - version 3.7
- seaborn - version 0.12.2

## Acknowledgements


## Contact
