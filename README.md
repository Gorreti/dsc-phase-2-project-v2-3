# King County House Sales Project

![image](https://github.com/Gorreti/dsc-phase-2-project-v2-3/homes.jpg)

## Business Problem

A real estate agency has given us a task to analyze house prices based on various features of the house. They want to know what kind of advice to give to homeowners when they want to buy or sell homes. They also need to know what features of a house a homeowner should focus on so as to increase the selling price of their homes.

## Data

I have used the King County House dataset so as to know what features of a house will increase the sale price of the houses. The insights from this project will be used to give advice to homeowners who want to buy or sell homes.

## Method of Analysis

I have used CRISP-DM methodology for this project. I have also used Linear Regression Modelling to get inferences on the sale price of the homes based on their features.

### Hypotheses

Null Hypothesis($H_0$): There is no relationship between the features of a house and the price.

Alternative Hypothesis($H_a$): There is a relationship between the features of a house and the price.

### Results

![graph](<https://github.com/Gorreti/dsc-phase-2-project-v2-3/price> and sqft_living.png)

The square footage of the living room is positively correlated to the price of a house.

### correlation of features

![graph](https://github.com/Gorreti/dsc-phase-2-project-v2-3/correlation.png)

### How the coefficients of bedrooms, square feet of living room, square feet of lot, floors and the year a house was built affect the price

![graph](https://github.com/Gorreti/dsc-phase-2-project-v2-3/features1.png)

The square feet for a living room has the highest positive effect on price followed by the number of floors in a house.
The year that a house was built has the highest negative effect on price meaning that as the house gets older, the price of the house also decreases.

### How condition and grade of a house affect the price

![graph](https://github.com/Gorreti/dsc-phase-2-project-v2-3/features2.png)

In terms of condition, a house whose condition is Very Good has the highest positive effect on price and a house with a good condition has the lowest positive effect on price.

In terms of grade, a grade 11 house has the highest positive effect on price and a grade 8 house has the lowest positive effect on price. Houses of grade 4, 5 and 6 decrease the price of the house.

Also, houses that have no waterfront compared to those with a waterfront reduce the price of a house, therefore, houses on a waterfront have a higher price than those that are not on a waterfront.

### Recommendations

* Increase the Square footage of living space.
* Ensure that the grade of your home is a grade 10(Very Good) and above.
* Ensure the condition for your home is very good.
* Having your home on a waterfront is an added advantage.
