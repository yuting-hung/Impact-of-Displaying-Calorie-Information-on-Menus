# Impact-of-Displaying-Calorie-Information-on-Menus

**Background/Introduction**

Obesity and overconsumption of high-calorie foods are prevalent issues in the United States. To address these concerns, policies and mandates have been implemented to require food manufacturers and retailers to label calorie information on their products, allowing consumers to make informed choices regarding their calorie intake. Additionally, in 2018 the FDA required food establishments with 20 or more locations to display Calorie information on their menus. Calorie information on restaurant menus is also becoming more widespread, even mandatory for all establishments in certain states, to help inform consumers and ultimately reduce the consumption of calorie-excessive foods. The purpose of this study is to determine whether the presence of calorie information on a restaurant’s menu affects consumer food choices.

**Research Question**

Does displaying calorie information on a restaurant’s menu affect consumer food choices?

**Hypothesis**

We hypothesize that including calorie information on restaurant menus will lead consumers to choose lower-calorie food options.

**Treatment & Experimental Design**

This study employed a within-subjects experimental design to investigate the impact of calorie menu labeling on food choices at a restaurant. The participants in this study ranged in age from 18 to 73 and were recruited from the local community. A diverse group of participants was recruited in terms of gender and occupation, with a total of 110 participants recruited for this study.

The survey began by collecting basic information from each participant, including age, gender, dietary preferences or restrictions, health conditions that affected food choices, and how often they ate out per week. Participants were then presented with a restaurant menu and asked to select the food items they would like to order. After making their initial selections, a second menu was shown that displayed the calorie count for each food item. Participants were asked to make their food choices again and explain whether or not they changed their selection after seeing the calorie information.

To assess the impact of calorie labeling, participants’ food choices before and after the treat- ment were compared. Additional information was gathered to gauge participants’ attitudes towards calorie information, like whether they typically considered it when making food choices, whether they were currently on a diet, and their estimated daily calorie intake and activity levels.

The data collected from this study was organized into a table with columns for experiment subjects, including their age, gender, as well as the number of participants in total. The table also included columns for participants’ food choices before and after the treatment, as well as their attitudes towards calorie information. By using a within-subjects design, individual differences in food preferences were controlled for, providing a more accurate assessment of the impact of calorie labeling on food choices.

**Target Outcome**

We measured the calorie count of the items chosen before and after presenting the treatment menu. The control menu was shown first without calorie information, and the treatment menu was shown after with calorie information. We used a paired T-test to measure the average treatment effect (ATE) and conditional average treatment effect (CATE) based on gender, health conscientiousness, and physical activity levels. We also used regression analysis to validate our results and provide further insights.

## Data Analysis
**Data Collection**

We collected data through a Qualtrics survey, which included demographic information, dietary preferences and restrictions, health conditions affecting food choices, and frequency of eating out. Each participant selected their food choices from the two menus presented, and we asked if the calorie information influenced their decision. We also gathered additional information to understand participants’ attitudes toward calorie information, such as whether they typically consider it when making food choices, whether they are currently on a diet, and their estimated daily calorie intake and activity levels.

**Data Cleaning & Preparation**

For Data Cleaning and Preparation, our initial step was to filter and extract relevant data from the raw excel table. We retained all participants’ responses to the questions and the “Duration (in seconds)” column, while removing irrelevant columns such as “StartDate”, “EndDate”, and “ResponseId”. Additionally, we excluded all participants who indicated that they did not want
to order anything to prevent dilution of the treatment effect.
We encountered anomalies in the “weight” column, likely due to participants’ different as- sumptions about weight units. To address this, we adjusted the anomalies to unit pounds. Similarly, the calorie intake was originally presented as a range, so we took the average for different ranges and used “1200” for the “< 1,600” option and “3400” for the “3000+” option.
To measure the impact of our calorie-labeling menu on food choice decision-making, we recorded participants who switched between two menus and transformed their ordered items from the two menus into actual calorie numbers. The code for this process can be found in the appendix.
For EDA, we examined people who don’t exercise and conducted Paired T-test Analysis. In the T-test on the entire population, we tested whether calorie posting on the menu truly has an impact on the total calories resulting from two orders. Our test results indicate that the total calories from the two menus differ for the calorie-matter group of people but not for the calorie-does-not-matter group (health conscientiousness).
Furthermore, we conducted a T-test conditioned on gender and found that the calorie-labeling menu has a significant impact on the calories consumed by females from food items they ordered on the regular menu and the calorie-labeling menu. We also conducted T-tests on exercise and did regression analysis using covariates to increase precision. Lastly, we used a power test to ensure that our sample size is suﬀicient for statistical significance.

**Within-study Design**

Since the study design was within-subjects, where each participant was exposed to both con- ditions (with and without the intervention), blocking, randomization, or clustering were not necessary. Within-subject designs aim to minimize the impact of individual differences and increase statistical power by using each participant as their own control, reducing variability and increasing sensitivity to detect treatment effects.
In a within-subject design, the order in which conditions are presented can be counterbalanced to control for order effects. Counterbalancing involves presenting the conditions in different orders across participants to ensure that any potential effects of order are distributed evenly across the groups. This approach can help increase the validity and reliability of the study’s results.
Overall, within-subject designs can offer several advantages, including increased power, reduced variability, and better control of potential confounding variables. By using each participant as their own control, within-subject designs can be a useful approach for investigating treatment effects and minimizing potential sources of bias.
