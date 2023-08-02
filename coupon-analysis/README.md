# Project Overview: Will a Customer Accept the Coupon?

## Overview

The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

## Data

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether they will accept the coupon if they are the driver. Answers such as the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

## Notebook : [Notebook]()

## Findings:
I analyzed two sets of coupons - Bars and coffee houses. The data is slightly skewed or have lesser data points in certain situations to be able to draw a concrete conclusion.
The findings based on the current data set are listed below:

  ### General
  - Drivers are more likely to accept a coupon when the weather is warmer (80F ) as compared to colder weather


  ### Bar
   
 - Drivers who visits bar more than 4 times a month are more likely to accept a bar coupon
 - Drivers who are above an age of 25 are more likely to accept the coupon
 - Drivers travelling alone or with friends are more likely to accept bar coupon
 - Drivers who tend to visit cheap restuarants over 8 times a month are more likely to accept the bar coupon

  ### Coffee House
  - The drivers who accept coupons visit the coffee house atleast once a month irrrespective of age, gender or income.
  - Drivers driving at 10 AM are most likely to accept a coupon
  - A male driver is most likely to accept coffee house coupon if they are 16 or younger.
  - A driver driving to a non urgent place is more likely to accept a coupon as compared to when driving to home or work
  - When a coupon location is shorter drive away, the likelyhood of it getting accepted is higher
  - Coupons with longer expiration (1day) have a higher acceptance rate compared to the ones expiring sooner.

## Next Steps:
  Analyze the coupons for restaurants and takeaways as well in a similar fashion and verify if the findings from coffee house and bar also applies to these categories.

  
