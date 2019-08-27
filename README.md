# HomepageABTest

For this side project, I have a synthetic dataset consisting of 294,479 observations of 50/50 split user visits to two homepage versions. The old homepage is the control group and the new homepage is the treatment group. Each visit has a binary indication of whether or not the user clicked a link and thus "converted". I am interested to understand the A/B results via hypothesis testing in two approaches--bootstrap sampling and logistics regression. P-values are generated for the A/B test to determine to what degree there was meaningful change in conversion rate for the new homepage. This project should help one better understand the steps needed to statistically determine A/B test results.

The z-score and p-value both indicate that there is a high chance of the observed conversion rate occurring if the null hypothesis is true. Thus, we fail to reject the null and cannot find sufficient evidence to say that the new homepage leads to more conversions.
