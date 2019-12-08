# Aimes, IA Housing Price Prediction Project

### Raymond R. Paller,  DSI-US-9-CHI Chicago


### Problem Statement

To predict the price of a house in Ames, IA, with data from previous residential real estate transactions,  using linear regression modeling techniques.


### Executive Summary

To gather and use data to make informed decisions and guide behavior is the raison d'etre for data science.  In this particular case the end objective is to predict residential real estate prices for the market of Ames, IA.  Such predictions have applicability to a number of end users including, but not limited to, the underlying buyers and sellers themselves and their interested third parties such as real estate agents, mortgage originators, appraisers;  local investors, government and governmental agencies are also potential end users.


Data was obtained from the [Ames, Iowa Assessor’s Office ][http://jse.amstat.org/v19n3/decock/DataDocumentation.txt]


The approach to modeling was to use linear regression (plain Linear Regression, Ordinary Least Squares, Ridge, and Lasso).
Metrics mainly consisted of Mean Squared Errors (MSE) and Coefficient of Determination (R squared).


### Conclusions and Recommendations

Fruitful results were obtained, as the final production model obtained good outcomes.   As seemingly always, additional improvements can be made.

Key points:

* Of the direct attributes of a house, overall quality ranked highest.  Also of prominence were gross living area, 1st
floor, basement, and garage area square footages;  rooms and baths and their respective locations;  type and style of house;     outer masonry, if any;  and year built and year of last remodelings (if any).

* Of supreme importance, the neighborhood location was of supreme importance.  This cannot be emphasized enough.  While living
in an average neighborhood is price immaterial, a superior neighborhood will help enormously,  while a substandard neighborhood
will be price penalized.  The middle is unremarkable, but the bookends -- particularly the higher bookends -- carry considerable heft.


### Notebooks

* [Complete Code Walkthru](code/complete_code_walkthru.ipynb)
* [Data Clean Up](code/data_clean_up.ipynb)
* [Iteration 1:  Numerical Features](code/iter_1.ipynb)
* [Iteration 2:  Categorical Features](code/iter_2.ipynb)
* [Iteration 3:  Feature Engineering](code/iter_3.ipynb)
* [Train Data](datasets/train.csv)
* [Test Data](datasets/test.csv)
* [Cleaned Up Data](datasets/cleaned_up_data.csv)
* [Final Model Data Kaggle Submission](datasets/iter_3_submission.csv)
* [Presentation Slides](campaign_to_predict_prices.pdf)
