# HypoTest
Program for hypothesis testing on TI calculators\
The reason this is on GitHub is because I'm still fixing bugs/errors and I might want to add features.
## Hypothesis Testing Program
Currently, we can do 7 different hypothesis tests:
1.  One-sample z test for μ (σ known)
2.  One-sample t test for μ
3.  Two-sample z test for μ (σ known)
4.  Two-sample t test for μ
5.  One-sample z test for p
6.  Two-sample z test for p when H<sub>0</sub> is not p<sub>1</sub>=p<sub>2</sub>
7.  Two-sample z test for p when H<sub>0</sub> is p<sub>1</sub>=p<sub>2</sub>
## Confidence Interval Program
This program is being tested. It is currently only usable as a subroutine accessed from the other program, after one of the above hypothesis tests is completed.
## Installation
The calculator program is on the file [Hypothesis_Test.8xp]. Download it and use a TI connection software, such as TI-Connect CE, to transfer it to a connected calculator. The name of the program on the calculator is "HYPOTEST". Download [Confidence_Interval.8xp] the same way, but only access it from the Hypotest program.
## Features to add
The following features may be added at some point in the future:
* Using the "CONFINT" program on its own
* Showing test statistic formulae
* Asking for H<sub>a</sub> instead of how many tails
* Visualising distributions with `ShadeNorm` and `Shade_t`
* Adding Hypothesis tests using Χ<sup>2</sup>
