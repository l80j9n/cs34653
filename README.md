java c
Econ 1150 Mini-Exam 4
1. You have estimated the following regression using data on 46,670 top executives in US corporations in 1990, where Earnings is their annual income earned, F emale is a binary variable that is equal to 1 if the individual is female and 0 otherwise, and M arketV alue and Return are the market value and stock market return of their corporation, respectively.

(a) Test the null hypothesis that the coefficient on Return is equal to zero at the 5% significance level.

So, we reject the null hypothesis at the 5% level of significance.
(b) Test the null hypothesis that the coefficients on all the explanatory variables are equal to zero at the 5% significance level.
(Note: The 5% critical value of the F3,∞ distribution is 2.60.)
We test the null hypothesis H0 : βF emale = 0, βlog(MarketV alue)=0,βReturn=0. There are 3 regressors in the unrestricted regression (k = 3) and 3 restrictions according to H0 (q = 3).
Note that the R2 of the restricted regression, RR2, is equal to zero since there are no regressors in the restricted regression. So, the F-statistic to test H0 is:

F is distributed according to the F3,∞ distribution. Since F = 8193 > 2.60, the 5% critical value of the F3,∞ distribution, we reject the null at the 5% level of significance.
2. We have the population regression:
Yi = β0 + β1X1i + β2X2i + β3X3i + ui
(a) Transform. the regression in order to use a hypothesis test on a single coefficient to test
H0 : β1 = β2 + β3.
H0 : β1 = β2 + β3 ⇐⇒ β1 − β2 − β3 = 0. So, we transform. the regression as follows:
Y = β0 + β1X1 + β2X2 + β3X3 + u
                                                                                                   = β0 + β1X1 + β2X2 + β3X3 + u − β2X1 + β2X1 − β3X1 + β3X1
                                   代 写Econ 1150 Applied Econometrics Mini-Exam 4
代做程序编程语言                                                 = β0 + (β1 − β2 − β3)X1 + β2(X2 + X1) + β3(X3 + X1) + u
Y = β0 + γX1 + β2V1 + β3V2 + u,
where γ = β1 − β2 − β3, V1 = X2 + X1 and V2 = X3 + X1.
(b) Describe how you would estimate this regression, construct the appropriate t-statistic, and test H0 at the 5% level of significance.
We estimate the transformed regression and obtain the coefficient estimate ˆγ. Then we construct the appropriate t-statistic to test H0 : β1 − β2 − β3 = 0 ⇐⇒ γ = 0:

We reject H0 at the 5% level of significance if |t| > 1.96.
3. Using American Community Survey Data, we obtain the regression results in Parts (a) and (b).
The variables are defined as follows:
❼ incwage: Income from wages
❼ log(incwage): The natural logarithm of incwage
❼ female: Binary variable that equals to 1 if the individual is female and 0 otherwise
❼ col: Binary variable that equals to 1 if the individual is a college graduate and 0 otherwise
❼ col × female: Interaction term between educ and female
(a) 
What is the marginal effect on income associated with going to college for a woman? What is the marginal effect on income associated with going to college for a man?

The marginal effect on wages associated with attending college for women is:
53940.86 − 24024.45 = 29916.41
The marginal effect on wages associated with attending college for men is:
53940.86
(b) 
What type of logarithmic regression is this (log-linear, linear-log, or log-log)? Interpret the coefficient on col.
(Note: You don’t have to algebraically derive this interpretation but you can check it if you want to.)
This is a log-linear regression.
Going to college is associated with a 69.9% increase in income from wages.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
