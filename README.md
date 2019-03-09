# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Stephen Godfrey, DSI-CC7-San Francisco

### Problem Statement

The question is what actions can be taken to increase the participation rates among high school students in taking the SAT and ACT college entrance exams? 

### Executive Summary

This project examines data covering participation rates and scores for students taking the SAT and ACT college entrance exam. The data are organized at the state level and contain 2017 and 2018 participation rates and Total, Composite and component scores (except ACT components for 2018 which are not available). This allows for a state-by-state comparison of participation rates and scores for each test. In addition, a second data set consisting of state-level income and population data is used to explore relationships between test participation and scores and state size and average income.

The data set is consistent with the observation that many states mandate one of the two tests as a requirement for high school graduation and the notion that students are likely to take only one of the two tests. Furthermore, a strong negative relationship between test participation and average test score is found. This means that states with low participation rates for a given test are likely to see higher average scores than a state with high participation rates on that same test. Comparison of average scores among states with large participation rate differences is not recommended.

A moderately strong positive relationship between average income by state and SAT participation is found. In other words, higher SAT participation rates are associated with higher state average incomes. And since ACT and SAT participation rates are negatively correlated, the reverse is found for ACT participation rates.

### Conclusions and Recommendations

Based on your exploration of the data, what are you key takeaways and recommendations? Choose one state with a lower participation rate and provide a suggestion for how the College Board might increase participation amongst graduating seniors in this state. Are there additional data you desire that would better inform your investigations?

Based on both an examination of the data and a review of state college entrance exam testing policy, it is clear that participation in such tests is heavily influenced by state policy towards testing. Currently, 29 states require that high school students take either the SAT or the ACT with no state requiring students take both.

To increase participation, states which have not already done so can consider making one of the two a mandatory high school graduation requirement. This policy provides several benefits to education systems and to students. One benefit is that it provides a college-level standardized test that can be used to benchmark students and to measure the efficacy of high-school educational systems. Students are helped in a couple ways. It guides students, usually in their junior year, to complete one common college application requirement. Having completed the requirement and knowing their score can be useful in directing students to consider appropriate schools. Integrating the test into the high school curriculum can also remove barriers to test taking such as the cost or the need to do it on a weekend.

Consider the case of Colorado which requires a standardized test as part of its high school accountability standards. After a review, the state education board switched from the ACT to the SAT but kept the requirement. The net effect was a large increase in the SAT participation coupled with a large drop in the ACT participation rate from 2017 to 2018. These participation rate changes were accompanied by large changes in average scores with the SAT average declining and the ACT average increasing. This case illustrates the typical outcome of making a test mandatory - a large drop in participation of the other test.

To address this, states will also need to encourage students to take both tests. Such encouragement might come in the form of an elimination of barriers by subsidizing fees and giving students time off for test taking and by converying the benefits of taking both tests to college counselors and advisors.

Analysis of incomes and test participation show a moderate positive correlation between SAT participation and average state per capita and household income. Since SAT and ACT participation rates are negatively correlated, this results in a negative correlation between ACT participation and income. Participation rates displayed little correlation with state population.

Further research into other influential factors, particularly into the benefits to students of taking both the SAT and the ACT, would be helpful to developing a strategy for increasing participation.


### Data

Data sources:
* 2017 and 2018 SAT and ACT data were provided as a part of project materials.  Comparisons were made by comparison to reports at these sites:

    * [SAT](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/)
    * [ACT](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows)


* Income and population data were sourced from Wikipedia at the link below with a further reference to the American Community Survey 1-Year Estimates at the link below:
    * [Wikipedia data](https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_income)
    * [American Community Survery](https://www.census.gov/programs-surveys/acs)

Updated data dictionary.

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|final_df|State of the data| 
|sat_part_2017|float|final_df|State participation rate for the SAT in 2017|
|sat_erw_2017|integer|final_df|State average SAT Evidence-Based Reading and Writing score in 2017|
|sat_math_2017|integer|final_df|State average SAT Math score in 2017|
|sat_total_2017|integer|final_df|State average SAT Total score in 2017|
|act_part_2017|float|final_df|State participation rate for the ACT in 2017|
|act_eng_2017|float|final_df|State average ACT English score in 2017|
|act_math_2017|float|final_df|State average ACT Math score in 2017|
|act_read_2017|float|final_df|State average ACT Reading score in 2017|
|act_sci_2017|float|final_df|State average ACT Science score in 2017|
|act_comp_2017|float|final_df|State average ACT Composite score in 2017|
|sat_part_2018|float|final_df|State participation rate for the SAT in 2018|
|sat_erw_2018|integer|final_df|State average SAT Evidence-Based Reading and Writing score in 2018|
|sat_math_2018|integer|final_df|State average SAT Math score in 2018|
|sat_total_2018|integer|final_df|State average SAT Total score in 2018|
|act_part_2018|float|final_df|State participation rate for the ACT in 2018|
|act_comp_2018|float|final_df|State average ACT Composite score in 2018|
|sat_change_part_17_to_18|float|final_df|2018 less 2017 SAT participation|
|act_change_part_17_to_18|float|final_df|2018 less 2017 ACT participation|
|sat_act_part_2017|float|final_df|2017 SAT less 2017 ACT participation|
|sat_act_part_2017|float|final_df|2018 SAT less 2018 ACT participation|
|state|object|inc_df_f|State of the data| 
|per_capita_income|float|inc_df_f|State per capita income 2010 - 2014|
|median_household_income|float|inc_df_f|State median household income 2010 - 2014|
|median_family_income|float|inc_df_f|State median family income 2010 - 2014|
|population|float|inc_df_f|State population|
|no_of_households|float|inc_df_f|State number of households|
|no_families|float|inc_df_f|State number of families|
|sat_part_group|float|inc_df_f|Binned state 2018 SAT participation|
|act_part_group|float|inc_df_f|Binned state 2018 ACT participation|


