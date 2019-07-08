# Recruit Restaurant Visitor Forecasting
## Predict how many future visitors a restaurant will receive
In this competition, you are provided a time-series forecasting problem centered around restaurant visitors. The data comes from two separate sites:

Hot Pepper Gourmet (hpg): similar to Yelp, here users can search restaurants and also make a reservation online AirREGI / Restaurant Board (air): similar to Square, a reservation control and cash register system You must use the reservations, visits, and other information from these sites to forecast future restaurant visitor totals on a given date. The training data covers the dates from 2016 until April 2017. The test set covers the last week of April and May of 2017. The test set is split based on time (the public fold coming first, the private fold following the public) and covers a chosen subset of the air restaurants. Note that the test set intentionally spans a holiday week in Japan called the "Golden Week."

There are days in the test set where the restaurant were closed and had no visitors. These are ignored in scoring. The training set omits days where the restaurants were closed.

**Project here is a partial data.** 

For this section Restaurant Visitors dataset was inspired by a recent Kaggle competition. The data considers daily visitors to four restaurants located in the United States, subject to American holidays. For the exogenous variable we'll see how holidays affect patronage.

The dataset contains 478 days of restaurant data, plus an additional 39 days of holiday data for forecasting purposes.
