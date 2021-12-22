# AIrBnB
Country Destination Prediction

The travel industry is one of the largest service industries in the world. In 2019, it
generated $1.9 trillion in economic output, in the United States. With eased up
COVID-19 regulations, a travel boom is expected. However, predicting a new user’s
travel destination poses an important problem to solve. In this project, we attempt to
solve this problem for Airbnb, a global travel giant, through combining an extensive
analysis of user information and session logs with machine learning techniques. Our
model can be utilized to personalize user experience as well as to forecast demands for
a particular destination.


To predict new user destinations, we have utilized user information, signup details and
session activity logs. All things considered, user-signup information like age, gender,
device type, language preferred give a measure of the likelihood of the user to book
from AirBnB while the session activities assist in narrowing down to the major activities
pertaining to the users who book.

We have data pertaining to users from the United States, their web session logs and
summary of destination countries.
(a) Users: account creation date, gender, age, preferred language, device type,
destination country, signup method, etc.
(b) Web sessions: user action, action detail, time spent on an action, device type.
(c) Countries: country name, latitude, longitude, distance from the United States,
destination language, language levenshtein distance from english as it is
preferred in the US.
(d) Age gender buckets: age bucket, country, gender, population in thousands, year.

Conclusions:
Age is playing a very important factor in deciding the destination. Younger people tend to go to
Countries like the Netherlands and Spain while older people tend to go to Great Britain.
People using Facebook as a login method have more booking tendency. One possible
hypothesis from this is that people sharing their facebook information want personalized
experience and are serious about booking.
AirBnB has assigned various numeric values to different signup flows. For example: One signup
flow could include verifying email addresses. People coming through some particular signup
flows have correlation to which country we are going.
1. Now whenever a new user signs up on the AirBnb website, they can predict where the
user wants to go through his information and sessions details.This will help them in
ramping up operations for the predicted country.
Group 50
2. Also they can personalize the experience for that user using ads, banner and discount
coupons and nudge him to actually make a booking.

