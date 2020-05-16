# Wine-variety-prediction
A predictive model for predicting the wine “variety”

The training Dataset consist of over 28 varieties of wine and 82,657 reviews of different wines.

The Data Description is as follows:
•	user_name - user_name of the reviewer
•	country -The country that the wine is from.
•	review_title - The title of the wine review, which often contains the vintage.
•	review_description - A verbose review of the wine.
•	designation - The vineyard within the winery where the grapes that made the wine are from.
•	points - ratings given by the user. The ratings are between 0 -100.
•	price - The cost for a bottle of the wine
•	province - The province or state that the wine is from.
•	region_1 - The wine-growing area in a province or state (ie Napa).
•	region_2 - Sometimes there are more specific regions specified within a wine-growing area (ie Rutherford inside the Napa Valley),
             but this value can sometimes be blank.
•	winery - The winery that made the wine
•	variety - The type of grapes used to make the wine. Dependent variable for task 2 of the assignment


Prediction of wine variety
* Model used : LinearSVC ( sklearn.svm.LinearSVC )  - LinearSVC is another (faster) implementation of Support Vector Classification
                                                      for the case of a linear kernel. it implements “one-vs-the-rest” multi-class 
                                                      strategy thus reducing the runtime significantly and also scale better to 
                                                      large numbers of samples. .

* Accuracy attained: 97.48 %
