https://bit.ly/3wu5gzq

# SalePricePrediction

Google Colab Link: https://drive.google.com/file/d/1mKDAjk42TU78kFflWxVz2TgK2oA9M-dQ/view?usp=sharing

<h1>House Price Prediction</h1>
<b>Objective:- To build a Linear Regression model that will be able to Predict the Sale Price of the house based on its characteristics.</b>

***Technologies used: Python, Machine learning technique - Linear Regression***

"""
#Conclusion

################Positive Significance/role#################

"zipcode_group_zipcode_group_4" is the most significant in this model :-
In real-world also, The location plays a major role in the Sale Price of the house


The "Area of the House from Basement" plays a major role in the "Sale Price" of the House.


Similarly, Overall grade has played quite significant role.

Some independent variable like "No of Bathrooms", "Lot Area", "No of Times Visited",
"Basement Area", "condition_of_the_house_excellent", "Waterfront View" have played Significant +ve Role.


Note:- Our model say that, The older houses are more expensive then the newer ones. - from plot of "Age of House",
So, this is New Knowledge.



#####################Negative Significance########################

from "Year Since Renovation" - As the time from the last renovation of the house is increased, the price 
of the house is decreased. In other word, Coustomer often prefer the houses that are recently renovated.

#################################################################

The most interesting interference is the role played by longitude and the latitude. We can infer from the plot
that longitude has significant -ve Significance, and the other hand latitude significant +ve significance.

***This Data is about the Houses of North America***

& if we interpret the geographical result from the Linear Regression model, The house in the North East region
have relatively higher prices than other place.

The information like this is where the essence of the data driven decision lies in.


"""

<h5>Result:- Generated the Prediction for test dataset with 84.62 % accuracy of the Model</h5>
