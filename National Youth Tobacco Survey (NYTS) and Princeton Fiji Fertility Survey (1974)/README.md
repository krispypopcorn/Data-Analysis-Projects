# Data Analysis using Analysis of variance for one-and two-way layouts, Generalised linear model - Binary and Poisson. 

## National Youth Tobacco Survey (NYTS):
src: https://www.cdc.gov/tobacco/data_statistics/surveys/nyts/index.htm
The NYTS was designed to provide national data on long-term, intermediate, and short-term indicators key to the design, implementation, and evaluation of comprehensive tobacco prevention and control programs. The NYTS also serves as a baseline for comparing progress toward meeting selected Healthy People 2020 goals for reducing tobacco use among youth:

* TU–18.1—Reduce the proportion of adolescents and young adults in grades 6 through 12 who are exposed to tobacco marketing on the Internet
* TU–18.2—Reduce the proportion of adolescents and young adults in grades 6 through 12 who are exposed to tobacco marketing in magazines and newspapers
* TU–18.3—Reduce the proportion of adolescents and young adults in grades 6 through 12 who are exposed to tobacco marketing in movies and television
* TU–18.4—Reduce the proportion of adolescents and young adults in grades 6 through 12 who are exposed to tobacco marketing at point of purchase (convenience store, supermarket, or gas station)
Items measured as part of the NYTS survey include correlates of tobacco use such as demographics, minors’ access to tobacco, and exposure to secondhand smoke.

* The NYTS provides nationally representative data about middle and high school youth’s—
 * Tobacco-related beliefs
 * Attitudes
 * Behaviors
 * Exposure to pro- and anti-tobacco influences
 
### Hypotheses: 
* Rural white males are the group most likely to use chewing tobacco
* There is reasonable certainty that less than half of one percent of ethnic-minority urban women and girls chew tobacco.

### Results:

* It is expected that 149.3 out of a 1000 rural white males have used chewing tobacco, snuff, or dip on 1 or more days in the past 30 days.
  * This outnumbers urban white males, urban hispanic males, urban black females and urban asian females with expected numbers (per 1000) 63.0, 31.5, 2.3 and 2.4 respectively.
  * Also note, the confidence intervals for the white, rural males does not overlap with any of the other categories.
  * Then we can say with reasonable certainty that rural white males are the group most likely to use chewing tobacco.
* Considering Females ethnic-minorities: it is expected that (2.4+2.3 = 4.7) subjects used chewing tobacco, snuff, or dip on 1 or more days in the past 30 days per thousand with Lower bound: 1.3 + 0.8 = 2.1 and Upper Bound: 4.2 + 6.8 = 11. [Following E[X] property of Binomials]
  * Which is = 0.47 percent (per 100). Note: 0.47 < 0.5.
  * However the 99% confidence interval ranges from 0.21% to 1.1%, so there isn’t reasonable certainty
  that less than half of one percent of ethnic-minority urban women and girls chew tobacco.




## Princeton Fiji Fertility Survey (1974)
The following description of this survey appeared in the 1991 edition of Dynamic Database: A Catalogue of Survey Data Files, Voorburg: International Statistical Institute.

Basic Information
Name of survey: Fiji Fertility Survey
Executive agency: Bureau of Statistics
Date of fieldwork: 1974
Universe: Ever-married women, 15-49
Coverage: National, 96%
Size: 4928
Weights: Self-weighting
Contents: WFS Core Mark 1
Supplementary surveys: Household members (n = 33,403, self-weighting); Re-interview (n = 371)

src: https://opr.princeton.edu/archive/wfs/FJ.aspx

### Hypothesis: 
* Improving girls’ education and delaying marriage will result in women choosing to have fewer children and increase the age gaps between their children. 
* Another hypothesis is that contraception was not widely available in Fiji in 1974 and as a result there was no way for married women to influence their birth intervals. Supporters of each hypothesis are in agreement that fertility appears to be lower for women married before age 15, likely because these women would not have been fertile in the early years of their marriage.

### Results:
* Regarding Hypothesis 1
  * The estimated fertility rate for women that are illeterate (literacy = no) is 0.984 ·
  0.303 (baseline fertility rate) = 0.298152 , hence lower than literate women.
  * Disregarding women married from the age of 14 and younger, since both hyoptheses agree that fertility appears to be lower for women married before age 15, likely because these women would not have been fertile in the early years of their marriage.
  * All other fertility rates related to ageMarried, are greater than the baseline (1), suggesting that delaying marriage may not result in women choosing to have fewer children and increase the age gaps between their children.
  * However, note that all these estimates are insignificant. Pr(>|z|) for most estimates is much greater than 0.05 (95% threshold). We cannot state any conclusions with high certainty. Also, the Likelihood ratio test in part b also tells us to consider the simpler model without literacy.
  
* Regarding hypothesis 2
  * There is no way we can form a conclusion on fertility rates before and after 1974 or on the impact
  the lack of contraception without further data and analysis.
