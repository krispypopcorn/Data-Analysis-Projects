# Data Analysis using Linear Mixed Models, Generalised linear mixed model and case/control model. 

## Netherlands School Data
* The data are adapted from Snijders and Boskers’ Multilevel Analysis, 2nd Edition (Sage, 2012)
* Dataset contains data on 760 Grade 8 students (i.e., most are 11 years old) in 32 primary schools in the Netherlands.


### Question of interest: 
* Which variables are associated with Grade 8 students’ scores on an end-of-year language test?: 


### Results:

* From our analysis it is evident that variables such as Verbal IQ (iq), Sex (sex), Socio-Economic Status of the student’s family (ses), the average socio-economic status of a school (mean_ses), and the average Verbal IQ of the school (mean_iq) have an impact on the end-of-year language test score and are statistically significant.
* The school a student goes to also seems significant in having an impact on the end-of-year language test score.
* Then the score on the end-of-year language test is not independent for each student. The factors mentioned above, do have an impact on the end-of-year language test score.


## National Youth Tobacco Survey (NYTS):

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
 
 src: https://www.cdc.gov/tobacco/data_statistics/surveys/nyts/index.htm


### Hypothesis:
* State-level differences in chewing tobacco usage amongst high school students are much larger than differences between schools within a state. 


### Question of interest:
* If one was interested in identifying locations with many tobacco chewers (in order tosell chewing tobacco to children, or if you prefer to implement programs to reduce tobacco chewing), would it be important to find individual schools with high chewing rates or would targeting those states where chewing is most common be sufficient?


### Results:
* According to our analysis, variance among schools is higher than the variance between states. Then the hypothesis that state-level differences in chewing tobacco usage amongst high school students are much larger than differences between schools within a state, is false.
* If one was interested in identifying locations with many tobacco chewers (in order to sell chewing tobacco to children, or if you prefer to implement programs to reduce tobacco chewing), it would be important to find individual schools with high chewing rates since schools explain a higher percentage of the variance in the model.

## Casualties involved in reported road accidents (RAS30)
src: https://www.gov.uk/government/statistical-data-sets/ras30-reported-casualties-in-road-accidents

* Dataset contains Road traffic accidents in the UK from 1979 to 2015. The data below consist of all pedestrians involved in motor vehicle accidents with either fatal or slight injuries (pedestrians with moderate injuries have been removed).

### Hypothesis
* Women tend to be, on average, safer as pedestrians than men, particularly as teenagers and in early adulthood. Explain which of the two models fit is more appropriate for addressing this research question.

### Results
* ‘theGlmInt’ (model2) with the Sex-Age interaction, has a majority of statistically significant estimates that significantly affect the odds of being a case. Then ‘theGlmInt’ is more appropriate for addressing this research question.
* Yes, UK road accident data are consistent with the hypothesis that women tend to be safer on average: 
  * Odds of being a Females case is 0.58 times the odds of being a Male case.
* On being safer as pedestrians than men as teenagers and in early adulthood:
  * The confidence intervals seem to overlap in the early half of childhood [0-7/8], hence nothing can be said with high certainty.
  * After the age of 7/8, women seem to be safer (as indicated by the data and Figure 2).
  
