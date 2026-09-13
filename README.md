# A-B-Testing-of-Different-Shopping-buttons-on-Eniac-s-website.

# Project Overview

The objective of this project was to determine which version of Eniac's "SHOP NOW" button performs best in encouraging visitors to click through to the iPhone shopping page.

Eniac wanted to increase sales of new iPhone models. Since the homepage prominently features an iPhone and provides visitors with a button to access the shopping page, the design and wording of this button could influence user behaviour.

The analysis investigates whether changing the button colour and wording leads to statistically significant differences in click-through rate (CTR).

# Background

Before conducting the experiment, Eniac's homepage received 50,061 visits during the period from October 13 to October 20, 2021. During this period, just under 2% of visitors clicked the "SHOP NOW" button, while the surrounding banner achieved a CTR of approximately 3.5%.

This raised the question of whether the button's visual design or its wording could be discouraging visitors from clicking it.

# A/B Test

The experiment ran from November 2, 2021 to November 16, 2021. The required sample size was determined using a statistical power of 80% and a minimum detectable effect of 20%. Based on an estimated CTR of 2% and approximately 7 142 daily visitors, the calculated requirement was 19,784 visitors per variation.

# Data

The analysis used experimental click data collected for each of the four homepage versions.

The datasets contained information about individual website elements, including the number of clicks each element received. The relevant data for the four button variants was extracted and aggregated into:

1. Number of clicks on the tested button
2. Number of visitors who did not click the button
3. Total visits
4. Click-through rate (CTR)

Sample Sizes:
A – White "SHOP NOW"	25,326	512	2.02%
B – Red "SHOP NOW"	24,747	281	1.14%
C – White "SEE DEALS"	24,876	527	2.12%
D – Red "SEE DEALS"	25,233	193	0.76%

# Metrics

Click-through rate (CTR): The percentage of visitors who clicked the button. A higher CTR indicates better performance.

# Statistical Analysis

A Chi-square test of independence was used to determine whether the differences in CTR between the four variants were statistically significant.

H₀: All four versions have the same CTR.
Hₐ: There is a difference in CTR between the versions.

The significance level was set at α = 0.05.

The overall test resulted in a χ² value of 213.34 and a p-value of 5.53 × 10⁻⁴⁶. The null hypothesis was therefore rejected, indicating a statistically significant difference between the four versions.

A Bonferroni-adjusted post-hoc analysis was then conducted. The comparison between Version A and C showed no significant difference (p = 0.589), while the comparison between the white-button group (A/C) and red-button group (B/D) was highly significant (p = 1.42 × 10⁻⁴⁵).

# Results & Conclusion

Version C – White "SEE DEALS" achieved the highest observed CTR at 2.12%, followed by Version A – White "SHOP NOW" at 2.02%. However, the difference between A and C was not statistically significant.

The analysis therefore shows that white button designs significantly outperformed red button designs in terms of CTR, but the data does not identify a statistically significant winner between A and C.

Key takeaway: White button designs performed significantly better than red designs. While Version C achieved the highest CTR, there is insufficient statistical evidence to conclude that it is superior to Version A.










