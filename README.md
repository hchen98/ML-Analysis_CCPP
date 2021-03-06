# ML Regression on CCPP dataset

Data Analysis through ML Regression on the Combined Cycle Power Plant dataset (2006-2011).

<br>

# Introduction

In this project, various regression models such as multi-linear, polynomial, SVR, Decision Tree Regression, and Random Forest Regression will be built in order to perform prediction of the net hourly electrical energy output (EP) of the plant. The dataset is from UCI ML dataset repository <a href="https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant">here</a>.


## Dataset

5 Features in total:

* Temperature (T)
* Ambient Pressure (AP)
* Relative Humidity (RH)
* Exhaust Vacuum (V)
* Net hourly electrical energy output (EP)

<br>

# Model Results
| Model Name | $R^2$ score | Adjusted $R^2$ score | MSE | RMSE |
| --- | --- | --- | --- | --- |
| Multiple Linear Regression | 0.9325315554761303 | 0.9323901862890713 | 19.733699303497644 | 4.44226285844249|
| Polynomial Linear Regression | 0.9458193300147094 | 0.9457058032048922 | 15.847186890065263 | 3.9808525330719378 |
| Support Vector Regression | 0.9480784049986258 | 0.9479696117141808 | 15.186434937782039 | 3.896977667087924 |
| Decision Tree Regression | 0.922905874177941 | 0.9227443359363023 | 22.549093991640547 | 4.748588631545224 |
| Random Forest Regression | 0.9615908334363876 | 0.9615103532550076 | 11.234213991640557 | 3.3517479009675766 |
