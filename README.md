# Coupons
Assignment 5.1: Will the Customer Accept the Coupon

## Goal
The goal of this project is to use the visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not.

## Data
This dataset is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk.

## Jupyter Notebook
Here is the link of the Jupyter Notebook with visualizations and probability distributions

## The Assignment
The assignment is to find out the differences between customers who did and did not accept the coupons.  And then to generate visualizations and probability distributions using python.

## Summary of findings

### A. General
1. the general acceptance rate of the coupons is 56.8%
2. the following is the bar chart of the acceptance rate of the coupons

![image_alt](https://github.com/StanleyWan/Coupon/blob/main/findings/Coupon_Type_Distribution.png)

3. The following is the histogram of the temperature column
![image_alt](https://github.com/StanleyWan/Coupon/blob/main/findings/temperature%20distribution.png)

### B. Bar Coupon Specific

1. Overall Bar Coupon Acceptance Rate: 41%

2. - Acceptance Rate for those drivers who go to the bar 3 or fewer times a month: 37.06%

   -  Acceptance Rate for those drivers who go to the bar greater than 3 times a month: 76.88%

3. -  Acceptance Rate for those drivers who visit bars more than once a month and the age is over 25: 77.21%

   -  Acceptance Rate for those drivers who visit bars once or less a month and the age is under 25: 38.38%

4. -  Acceptance Rate for drivers that visit bars >1 time a month, the occupation is not farming, fishing, or forestry, and passengers are not kids: 77.49%

   -  Acceptance Rate for drivers else: 37.19%

5. -  Acceptance Rate for drivers that (visit bars >1 time a month, passengers were not kids or widowed), or (visit bars >1 time a month and the age <30), or (visit cheap restaurants >4 times a month and income >50K): 58.73%
   -  Acceptance Rate for drivers else: 54.76%
     
## Hypothesize
Those drivers who are high frequentcy of Bar visiting, the age between 25-30,  the occupation is not framing, fishing or forestry and the passengers are not kids will very likely accept the bar coupon.

# Independent Investigation
Analysis focused on drivers who accept the Coffee coupons

## Summary of findings
1. Acceptance Rate for the Coffee Coupon for the driver whose age <25 is : 55.01%
2. Acceptance Rate for the Coffee Coupon for the driver whose age is between 25-35 is: 49.86%
3. Acceptance Rate for the Coffee Coupon for the driver whose age is between 35-50 is: 56.45%
4. Acceptance Rate for the Coffee Coupon for the driver whose age is >50 is not available

![image_alt](https://github.com/StanleyWan/Coupon/blob/main/findings/age_group.png)

5. Acceptance Rate for the Coffee Coupon for the driver who visit coffee shop 1-3 is: 64.78%
6. Acceptance Rate for the Coffee Coupon for the driver who visit coffee shop 4-8 is: 68.59%
7. Acceptance Rate for the Coffee Coupon for the driver who visit coffee shop greater than 8 is: 65.79%
8. Acceptance Rate for the Coffee Coupon for the driver who visit coffee shop less than 1 is: 48.19%
9. Acceptance Rate for the Coffee Coupon for the driver who never visit coffee shop is: 18.88%

![image_alt](https://github.com/StanleyWan/Coupon/blob/main/findings/coffee_visit.png)

## Hypothesize
From the data findings,  the high frequency coffee shop goers will very likely accept the coffee coupons.
