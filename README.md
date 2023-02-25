# t_company_data_analyst
The test for data analyst. Estimated time is 2 hours.
Here is [solution](https://github.com/voleka-ocrv/turing_data_analyst/blob/main/turing_test.ipynb).

## Question 1: 
Which country has the 3rd death rate? Death rate: total number of death per million inhabitants.
- [ ] Italy
- [x] Andorra
- [ ] USA
- [ ] Belgium
- [ ] Spain

## Question 2: 
How tall are the tallest 1% of people?
- [ ] They are taller than 186 cm
- [ ] They are taller than 175 cm
- [ ] They are taller than 147 cm
- [x] They are taller than 184 cm
- [ ] They are taller than 191 cm

## Question 3: 
Which two features have the highest spearman rank correlation?
- [ ] Age and weight
- [ ] Age and blood presure
- [x] Blood presure levels (ap_hi, ap_low)
- [x] Gender and height

## Question 4: 
Do people over 50 have higher cholesterol levels than the rest?
- [ ] Yes, their cholesterol level is 29% higher on average
- [x] No, it's about the same
- [ ] No, people over 50 have 7% lower cholesterol level
- [ ] Yes, their cholesterol level is 14% higher on average
- [ ] Yes, their cholesterol level is 19% higher on average

## Question 5: 
How much heavier the age group with the highest average weight than the age group with the lowest average weight?
- [ ] 45% havier
- [x] 28% havier
- [ ] 13% havier
- [ ] 87% havier
- [ ] 9% havier
(Please, load "cardio_base.csv". This is a health dataset. Each row represents a person and corresponding attributes like age, height, weight, blood pressure, cholesterol level, etc. When asked about age, please calculate with age in years rounded down.)

## Question 6: 
Which of the following statements is true with 95% confidence?
- [ ] Smokers have higher blood pressure than non-smokers
- [x] Smokers have higher cholisterol level than non-smokers
- [ ] Smokers weight less than non-smokers
- [x] Men have higher blood pressure than women (???)

## Question 7: 
What is the probabilyty that a country has GDP over $10 000, if we know that they have at least 5 hospital beds per 1000 inhabitants?
- [ ] 92%
- [x] 88%
- [ ] 71%
- [ ] 54%
- [ ] 39%

## Question 8: 
What is the F1 score of the following statement: 
Countries, where more than 20% population is over 65 years old, have death rates over 50 per million inhabitants. Ignore countries, where any of the necessary information is missing!
- [ ] 0.15
- [ ] 0.73
- [ ] 0.87
- [x] 0.18
- [ ] 0.21

## Question 9: 
Are men are more likely to be smoker than women? The data contains information to identify gender IDs!
- [x] Yes, men are 12x more likely to be smokers
- [ ] Yes, men are 7x more likely to be smokers
- [ ] Similar portion of men and women are smokers
- [ ] No, women are 12x more likely to be smokers

## Question 10: 
Look at the cumulative number of confirmed cases in Italy between 2020-02-28 and 2020-03-20. Fit an exponential function (y = Ae^(Bx)) to this set to express cummulative cases as function of days passed, by minimizing squared loss. What is the difference between the exponential curve and the total number of real cases on 2020-03-20?
- [ ] 11756
- [ ] 37414
- [ ] 187963
- [ ] ~0
- [ ] 9785

## Question 11: 
When did the difference in the total number of confirmed cases between Italy and Germaty become more than 10 000?

Second dataset COVID-19 cases. This dataset contains daily COVID-19 cases for all countries in the world. Each row represents a calendar day. The rows also contains some simple information about the countries, like population, percentage of the population over 65, GDP, and hospital beds per 1000 inhabitants. 
- [ ] 2020-02-28
- [ ] 2020-02-29
- [ ] 2020-03-16
- [ ] 2020-03-12
- [ ] 2020-03-01

## Question 12: 
What percentage of people are more than 2 standard deviations far from the average height?
- [ ] 5%
- [ ] 3%
- [ ] 2%
- [ ] 7%
- [ ] 11%


Appendix:

[Interesting resource](https://ethanweed.github.io/pythonbook/05.02-ttest.html#)
