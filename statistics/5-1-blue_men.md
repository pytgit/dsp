[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

### How many people are between 5'10" and 6'1"?
First I converted 5'10" and 6'1" into cm, which are 178am and 185cm respectively.

Then, using the following python code:

````python
dist.cdf(185)-dist.cdf(178)
````
The percentage of people between 5'10" and 6'1" is approximately *32%*.
