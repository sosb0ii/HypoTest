# HypoTest
Program for hypothesis testing on TI calculators\
The reason this is on GitHub is because I'm still fixing bugs/errors and I might want to add features.
## Installation
The programs on this branch are only compatible with the other programs on different branches. The three funcitonalities (hypothesis test, confidence interval, and condition check) are all accessed from the "STATS" program. Directly running one of the other programs will (probably) work, but it will not be able to change to a different program (e.g. hypothesis test to condition check). To properly run these files on your calculator,
1. Go to the "central-stats-program" branch of this repository. (this branch)
2. Download the four .8xp files
3. Transfer them to your calculator via a TI connection software, such as [TI-Connect CE](https://education.ti.com/en/products/computer-software/ti-connect-ce-sw).
4. Run the program titled "STAT". Follow along to do whichever function you like.
# Hypothesis Testing Program
Currently, we can do 7 different hypothesis tests:
1.  One-sample z test for μ (σ known)
2.  One-sample t test for μ
3.  Two-sample z test for μ (σ known)
4.  Two-sample t test for μ
5.  One-sample z test for p
6.  Two-sample z test for p when H<sub>0</sub> is not p<sub>1</sub>=p<sub>2</sub>
7.  Two-sample z test for p when H<sub>0</sub> is p<sub>1</sub>=p<sub>2</sub>
# Confidence Interval Program
This program makes a confidence interval for µ or p (1 or 2 populations). When accessing it after completing a hypothesis test, you can skip the step where you enter information
# Condition Check
Check the test statistic conditions.
# Features to add
The following features may be added at some point in the future:
* Showing test statistic and confidence interval formulae
* Fleshing out the Options menu under the π special menu
* Asking for H<sub>a</sub> instead of how many tails
* Visualising distributions with `ShadeNorm` and `Shade_t`
* Adding Hypothesis tests using Χ<sup>2</sup>
