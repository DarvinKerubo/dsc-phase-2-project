# Phase 2 Project

## Project Overview

For this project, you will use regression modeling to analyze house sales in a northwestern county.

### The Data

This project makes use of the King County House Sales dataset, which is available in the data folder of this repository as kc house data.csv. Column names.md, which is located in the same folder, has a description of the column names. Like most real-world data sets, the column names are not completely described, so if you have any questions about what the data means, you'll need to do some research or use your best judgment.

### Business Problem

 I want to create a model with these data that will allow me to forecast the price of a house using the characteristics of the data about the house. We can help both the seller find their business in this situation. The model can be used by the seller to estimate the selling price of their home and determine whether any renovations are necessary before they can sell it. Based on their budget, the buyer may receive some recommendations for the type of home they can afford.
 

## Deliverables

There are three deliverables for this project:

* A **GitHub repository**
* A **Jupyter Notebook**
* A **non-technical presentation**

Review the "Project Submission & Review" page in the "Milestones Instructions" topic for instructions on creating and submitting your deliverables. Refer to the rubric associated with this assignment for specifications describing high-quality deliverables.

### Key Points

To the point of goal:

Remove information from the pricing that has no meaning or is null.
Remove any features that don't increase the value of the home.
Delete any null values
Using scatter plots and qqplots, see if there are any highly connected characteristics that may be deleted.
construct the model of linear regression.
analyze how the features can affect the price of the house

I polished most of the columns that didn't add to the cost of the home and removed them.

The ID has nothing to do with the cost.
Separate the date file into the year and month.
I need to eliminate the lat and long data because of how strongly they connect to the zipcode.

Summary

The comparison of predicted and actual data reveals that, for the majority of houses with modest prices (20% of the maximum price), the predicted price is fairly similar to the actual price. While the house price is not too high, qqplot demonstrates that the house price is accurately forecast. But, the projection is not very accurate for the high value price house. When a house's worth increases, especially when it costs more than a million dollars, there is a significant movement in the predicted price.