[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

### Means
Actual mean is 1.024205155043831.
Biased mean is 2.403679100664282.

### Plot of actual and biased disitributions

Python code used:
```python
width=0.45
axis = [0, 6, 0, 0.6]
thinkplot.Pmfs([child_pmf, biased])
thinkplot.Config(xlabel='# children in family', axis=axis)
````

![Plot of actual and biased disitributions](./img/plot.png)

