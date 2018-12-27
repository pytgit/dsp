[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

## Are first babies lighter or heavier?

Mean weight for first babies is 7.201, compared with other babies' mean weight of 7.326, and so first babies tend to be slightly lighter than others. 

Python code used:
````python
firsts.totalwgt_lb.mean(), others.totalwgt_lb.mean()
````

## Cohen's effect size between groups

The Cohen's d between first babies' weight and others' weight is -0.0887, showing that there's not a large difference between first or other babies' weight (). When compared with the different in pregancy length (Cohen d = 0.0289), weight has a slightly larger effect.

Python code used:
````python
CohenEffectSize(firsts.totalwgt_lb, others.totalwgt_lb)
````
