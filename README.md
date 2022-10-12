# wildfire
This repo contains a paper that teammates and I wrote, called "Machine learning for wildfire prediction from meteorological data in California and Nevada, USA". Below is the abstract.

*This project used meteorological data to predict
wildfire ignitions, temporally within 10-day
windows, spatially within roughly 25 km of
weather locations in California and Nevada, USA,
using data from 2001-2010. Predictions were for
ignitions in the same temporal window as the
weather, which is not designed for short-term
predictions based on current-moment weather, but
is useful for creating a susceptibility map which
informs long-term risks in the area. The best
results were found using a 10-day temporal
resolution, joining the fire data to the nearest
weather station, imputing missing values using the
mean, and scaling features using standard scaler.
The best machine learning algorithm was a
soft-voting classifier composed of a closed-form
logistic regressor, a stochastic gradient descent
classifier, and a random forest classifier and had
an F1 score of 0.5138. This model with adjusting
the threshold values achieved recall of 0.9880 and
precision of 0.2020, which is better than results
found in previous work optimized for Yunnan
Province, China. Going forward, this project
could be adjusted to optimize for short-term
predictions, or could be applied to other regions of
the globe.*
