# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis Overview

Julia Tsaltas
June 18, 2021

### Problem Statement

As some states require all students to take the SAT ([*source*](https://blog.prepscholar.com/which-states-require-the-sat)) or ACT ([*source*](https://blog.prepscholar.com/which-states-require-the-act-full-list-and-advice)), administrators in these states argue that by making all students participate in testing could encourage some students who wouldn't otherwise take the test to maybe consider applying to college since they already have completed the testing requirements ([*source*](https://blog.prepscholar.com/which-states-require-the-sat)).

However, research has shown correlations between family income levels and test scores including dramatic differences in scores between Black and White students of low family income levels ([*source*](https://www.researchgate.net/publication/280232788_Race_Poverty_and_SAT_Scores_Modeling_the_Influences_of_Family_Income_on_Black_and_White_High_School_Students%27_SAT_Performance)).

This project looks to determine if, more broadly, a state's median income correlates to SAT/ACT test scores.

Does a state’s median income correlate with the state’s average test score?

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|The name of each state including District of Columbia|
|act_avg|float|ACT|Average ACT score percentage per state|
|sat_avg|float|SAT|Average SAT score percentage per state|
|act_part_avg|float|ACT|Average ACT score percentage per state|
|sat_part_avg|float|SAT|Average SAT score percentage per state|
|med_income|float|2015-2019 American Community Survey 5-Year Estimates|Median income per state|

### Brief Summary of Analysis

There is a score-income correlation present between each of the ACT and SAT scores and the median income of the states, but it is dependent also on the state's participation rates of each of the test scores as well. 

The ACT has greater participation rates overall with many schools requiring mandatory attendence compared to the SAT test where no state has 100% average participation between 2017 and 2019. For ACT tests, there is a high participation of over 80% for 20 of the 51 states (including DC), while only 8 of the 51 states have over 80% participation.

The ACT test scores showed a positive correlation when compared to the state's median income, while the SAT showed a negative correlation between scores and income. The outcomes of these correlations are attributed to both the impact of income on test scores as well as participation rates. For the ACT where participation is stronger than the SAT test, there is a positive correlation of 0.58 between state average scores and the state's median income, but for the SAT test where there is less participation overall and 20 of the 51 states have less than 20% participation, a negative correlation resulted where the higher income states had higher participation rates as well which had a negative effect on the state's average test scores. The negative correlation between participation and scores is also seen between the two test types. The ACT had higher participation and lower averal scores than the SAT test, so the more participation from student's who would otherwise not want to take the test will lower the state's overall average.


### Conclusions

Even when comparing broad score and income averages per state versus comparing income and scores of individual students, there is still a correlation between income and test scores, particularly when participation is high among a larger range of income levels. Once participation levels become lower, the overall test scores become higher. This could be attributed to an increase of students participating who would not otherwise want to do the test and get lower scores. As shown when participation is high across a range of income levels, such as with the ACT scores versus median income, amongst those states there is a positive correlation between income and scores.

### Recommendations for future studies

In the wake of the COVID-19 pandemic, many colleges are dropping standardized testing requirements for admissions in 2021 and some colleges will even drop testing requirements up until 2025. With the increase in studies highlighting how financial inequities influence the score outcomes and not necessarily the student's post-secondary success, there is opportunity to now study student success in post-secondary academics when there is less admission weight on standardized testing.

However, with continued income inequality, it is still important to provide more funding and resources to in-need communities through the form of direct funding to schools or subsidized tutoring for lower income families.