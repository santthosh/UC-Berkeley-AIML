# Assignment 5.1


## Goal

“Will a customer accept the coupon?” The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

## Data

The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

## Findings and Results 

All the visualizations and work items are documented in this [Notebook](notebook.ipynb) 

### Investigating Bar Coupons

* Frequent Bar visitors who visited more than 3 times a month are **twice** more likely to accept the coupons than infrequent visitors who visited 3 or less times in a month

* Group of users visiting bar more than once a month and are of age group > 25 are **2 times** more likely to accept the coupons than everyone else

* Group of users who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry are **2.4 times** more likely to accept the coupons

* Group of users who 
  * go to bars more than once a month, had passengers that were not a kid, and were not widowed OR
  * go to bars more than once a month and are under the age of 30 OR
  * go to cheap restaurants more than 4 times a month and income is less than 50K.

 are also **2.4 times** more likely to accept the coupons
 
 ### Independent Investigation
 
 For the independent investigation, we took the Coffe House coupons in comparison with characteristics of passangers who accept the coupon. From analysis determined that
 
 * Drivers driving alone are more likely to accept the coupons and make up the dominant portion of this group
 
 * Drivers with friends traveling when the temperature is in 80s is **1.26 times** more liekly to accept the coupons compared to others 


## Next Steps and Recommendations

* Next Step: Enrich this data set with more clear identification of income levels so we can articulate which coupons work where. We understand lower income drivers accept coupons more

* Provide coupons to lower income groups and groups that are more likely to accept it 

* People are more likely to accept coupons when the weather is sunny (80s) than others 
