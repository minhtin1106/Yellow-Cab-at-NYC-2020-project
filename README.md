# Yellow cab NYC 2020 dataset- Data analytics and predictions with Python

__Introduction__:<br>
The motivation for me to work on this project is:<br>
+ firstly, help the policy makers gain a clearer view of how the traffic pattern changes during the pandemic 
+ secondly, help taxi companies to compete better in the market by gaining trip distance, and fare amount visibility with our ML models. 

__Scope__: <br>
The data captured all taxi trips in 2020 in New York city having 24 millions of rows in total and collected by NYC Government. In the notebook, I sampled and worked on 10% of the whole dataset. 

__Tasks__:<br>
+ Preprocessed data (i.e: dealing with unrealistic values due to errors in data entry,  missingness, inappropriate data types,  inconsistency of unit of measurement, etc)
+ Visualized the data in the intuitive way with suitable graphs to see different aspects such as trips number, payment type, etc
+ Built regression models to predict trip distance, fare amount, and classification model to predict payment type

__Results__:<br>
+ For fare amount:<br> 
I successfully constructed the parsimonious model using 1 strongest feature (i.e: distance) being able to capture 85% variance of the fare amount. 

+ For trip distance:<br>
The R_squared was a bit low  (i.e: .38) but I found that there was room for improvement by including the information about  the destination information. That informtion made sense to be included since the passenger often know beforehand where they want to drop off.
