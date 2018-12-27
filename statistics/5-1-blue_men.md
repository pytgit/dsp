[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

### How many people are between 5'10" and 6'1"?
First I converted 5'10" and 6'1" into cm, which are 177.8cm and 185.42cm respectively.

Then, using the following python code:

````python
dist.cdf(185.42)-dist.cdf(177.8)
````
The percentage of people between 5'10" and 6'1" is approximately *34%*.
