---
layout: post
title: Recover Differential Rotation using ML?
---

We showed in Aigrain et al. (2015) that, so far, nobody has an accurate way to recover differential rotation from simulated light curves.

The most promising approaches revolved around studying the power spectrum or periodogram. The main peak (due to rotation) would be broadened or split.

However, this signature can also be caused by starspot decay and evolution, or the appearance of many spots, even without any differential rotation in our model (alpha).


I hypothesized that the periodogram peak structure might be able to recover some type of combined parameter that includes many of these degenerate stellar properties. Perhaps this would be enough information to be useful to theorists?

My attempts to find such a "starspot evolution parameter" based on the peak broadening in the periodogram has not shown any correlation with simulated properties from the Aigrain model light curves. I also tried a simple Random Forest regression of the peak width (and width relative to the period) versus every simulated property for all 1000 light curves. Nada

So the question/idea is: can we invert the problem, do machine learning on the power spectrum or periodogram itself to try and learn what the features of interest are? A giant amount of simulated light curves (even just using a super crappy evolving sine-curve code) would be helpful to tease out results....