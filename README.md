# US-Crime-Analysis
This project was done in conjunction with class ISYE 6501 at the University of Georgia. It was written exclusively in R.
### Project Objective
Using the data set file uscrime.txt (http://www.statsci.org/data/general/uscrime.txt, http://www.statsci.org/data/general/uscrime.html), I tested various methods of model building and variable selection to find the model with the lowest MSE.
The method used are:
1. Linear Regression
2. Linear Regression with Box-Cox transformation
3. Principal Component Regression
4. Regression Tree
5. Random Forest
6. Stepwise Regression
7. Ridge Regression
8. LASSO

### Description of Data set
Criminologists are interested in the effect of punishment regimes on crime rates. This has been studied using aggregate data on 47 states of the USA for 1960. The data set contains the following columns:

Variable | Description
-------- | -------------
M		     |percentage of males aged 14–24 in total state population
So   	   |	indicator variable for a southern state
Ed	     |	mean years of schooling of the population aged 25 years or over
Po1	     |	per capita expenditure on police protection in 1960
Po2	     |	per capita expenditure on police protection in 1959
LF	     |	labour force participation rate of civilian urban males in the age-group 14-24
M.F	     |	number of males per 100 females
Pop	     |	state population in 1960 in hundred thousands
NW	     |	percentage of nonwhites in the population
U1	     |	unemployment rate of urban males 14–24
U2	     |	unemployment rate of urban males 35–39
Wealth   |		wealth: median value of transferable assets or family income
Ineq     |	income inequality: percentage of families earning below half the median income
Prob	   |	probability of imprisonment: ratio of number of commitments to number of offenses
Time	   |	average time in months served by offenders in state prisons before their first release
Crime	   |	crime rate: number of offenses per 100,000 population in 1960
