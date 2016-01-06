# Statistics: A Brief Overview
Statistics has become a big part of medicine and other disciplines, we must understand them.

###Definitions
Mean - average those bad boys

Median - what is the middle number (good for skewed datasets)

Distribution - The same of the datas curve.
- Normal (AKA Gaussian) - bell curve and mean = median. The larger the sample size, the more closely the distribution will be to normal

Standard Deviation - how far away from the mean an individual value lies

P Value - Probablility that the observed outcome was the result of chance. P<.05 was arbitrarily chosen, meaning there is less than a 5% chance that the observed value was seen at chance. If a p value is outside of the range, there is either no "real" difference between the 2 sets of data, or the sample size was too small. No way to differentiate using p value.

Confidence Interval (CI) - range in which it is fairly certain the true value lies (95% is frequently used). If 0 is in the interval, then there is no statistical signficance, rega

###Types of Data
Numerical Data - The number itself has relevance

Categorical Data - Nonnumerical values (sex, city)

###Statistical Tests
Parameteric Tests - Assume normal distribution, requires a large sample size. Since the distribution is known, the tests can identify smaller differences than nonparametric tests

Nonparametric Tests - Make no assumptions about the distribution of the data. This makes these tests ignore the absolute values of data points and focus on ordinal properties.

For each parameteric test, there is an analogous nonparametric test

| Parametric  | Nonparametric |
| ------------- | ------------- |
| Chi-square test  | Fisher exact test  |
| Paired Student t test  | Wilcoxon signed rank test  |
| Unpaired Student t test  | Mann-Whitney U test  |
| ANOVA by sum of squares  | ANOVA by rank  |
| Pearson product moment coefficient  | Spearman rank correlation  |

Chi-square - Use a large sample size of categorical data in 2 or more independent data sets compared with a theoretical distribution. Chi-square of 0 means there is no relationship between the samples.

Fisher Exact Test - Nonparametric test for categorical data. It can be used with small data sets.

Student t Test - 
