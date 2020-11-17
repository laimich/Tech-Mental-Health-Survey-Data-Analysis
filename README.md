# Data Analysis of Mental Health in the Tech Industry
Data set: [Kaggle](https://www.kaggle.com/anth7310/mental-health-in-the-tech-industry)

### Purpose
- Combine usage of SQL and Python in Jupyter
- Use public data set that is structured and has multiple tables
- Perform data analysis with data frames and advanced SQL queries
- Create different data visualizations using seaborn and matplotlib
- Correlation vs Causality
- How is mental health handled in the tech industry? 
   - Compared to non tech industry?
   - How has it changed overtime? 
   - Has the tech industry become more accepting/open to mental health?

### Questions
1. Ease level for taking medical leave for mental health conditions at work?
   - Compare how results differ for tech employers vs non tech employers.
2. Do people think discussing mental health issues with their employer would have negative consequences?
   - Compare how results differ for tech employers vs non tech employers.
3. How much importance do employers place on mental health? How about in comparison to physical health? 
   - Compare the distribution of ratings for each question, mental health and physical health.
   - Compare how both results differ for tech employers vs non tech employers.
4. Based on age, how well do people think the tech industry supports employees with mental health concerns?
   - Compare overtime by the survey years, 2017, 2018, and 2019.
5. Have people observed or experienced a supportive response to mental health at work? How about in comparison to an unsupportive response?
   - Compare the distribution of responses for each question, supportive and unsupportive.
   - Compare how both results differ overtime by the survey years, 2017, 2018, and 2019.

### Conclusions

##### Question 1
- Almost half of the responses said they 'Don't know' how easy it is to take medical leave for a mental health condition at their job. This poses the question of why they don't know, there are many possibilities such as, employers not sharing their medical leave options, employees not considering medical leave for mental health, and the awareness of mental health as a society.
   - Refer to [Plot 1](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot1b.png) and [Table 1](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/table1b.png). 
- Since this data set seems to have surveyed more people with tech employers, I used the percentages of responses to compare tech employer vs non tech employer. The two most frequent answers for taking medical leave for a mental health condition at work, is the same for tech employer vs non tech employer, with each approximately 40-45% saying 'Don't know' and approximately 20% saying 'Somewhat easy'. Since this also makes up almost two third of responses, we can say there aren't major differences in the ease level of taking medical leave for a mental health condition for someone with a tech employer vs non tech employer. 
   - Refer to [Plot 1b](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot1b.png) and [Table 1b](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/table1b.png). 

##### Question 2
- People with non tech employers mostly answered 'Maybe' to if they think discussing a mental health issue with their employer would have negative consequences. People aged 20-30 mostly answered 'Maybe' or 'No' to negative consequences. While people aged 35-45 mostly answered 'Maybe' or 'Yes'. This could mean the younger generation are a bit more willing to discuss mental health issues with their non tech employers. There are slightly more people answering 'Yes' in comparison to 'No'. Although, since most of the responses are 'Maybe', we can conclude that people are unclear about the results of discussing mental health with their non tech employers. 
   - Refer to [Plot 2](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot2.png)
- People with tech employers mostly answered 'Maybe' or 'No' to if they think discussing a mental health issue with their employer would have negative consequences. In comparison to the 'Maybe' answers for non tech employers, there is a significant difference where less tech employer people answered 'Maybe'. The most 'Maybe' answers occur in the 25 to 35 age range. While the most 'No' answers occur in the 25 to 32 age range.
   - Refer to [Plot 2b](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot2b.png)
- In comparison to people with tech employers vs non tech employers, people with tech employers seem more aware of not having negative consequences when discussing mental health issues with their employer.

##### Question 3
- For the importance rating that employers place on mental health, the most common rating answered is 5 out of 10. The next most common ratings are 3, 6, 7, 8. This means most people feel that their employers give mental health an average importance, with a slight skew towards higher ratings. In comparison to tech employer vs non tech employer, ratings on the lower end of 0-2 seem to consist of a higher occurrence of non tech employers than the other ratings. Whereas, ratings on the higher end of 8 and 10 seem to consist of a higher occurrence of tech employers than the other ratings.
   - Refer to [Plot 3](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot3.png)
- For the importance rating that employers place on physical health, the most common rating answered is 5 or 7 out of 10. The next most common ratings are 6 and 8. Most people must feel that their employers give an average to above average importance on physical health. There are very few answers giving a rating 4 or less. 
   - Refer to [Plot 3b](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot3b.png)
- From comparing the common ratings for mental health importance vs physical health importance, we can see that employers show more importance to physical health. In comparison, the mental health ratings are more distributed around all ratings with the most around 5 or 7. The physical health ratings are clumped together around 5-8. We can conclude that employers seem to place more importance on physical health in comparison to mental health, with the importance on mental health being more distributed and possibly unclear to employees. 

##### Question 4
- People rated the tech industry for how well they support employees with mental health issues, with a majority of ratings given as 2 or 3 out of 5. The next most common ratings are 1 and 4 where 1 ratings have the most occurrences in the 30 to 45 age range and 4 ratings have the most occurrences in the 25 to 35 age range. Very few people gave the best rating of 5. For the most part, people think the tech industry is giving average or below average support to employees with mental health issues. This also supports our findings from part of Q3, where people rated the importance their employers place on mental health.
   - Refer to [Plot 4](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot4.png)
- From looking at the changes in ratings for 2017, 2018, and 2019, we can see that overtime, there is an increase of people giving a rating of 1 or 4 and a decrease of people giving a rating of 5. As time passes, the age for ratings of 1 increases while the age for ratings of 5 decreases. Overall it seems that people believe the tech industry is doing slightly worse overtime with the mental health support given to their employees.
   - Refer to [Plot 4b](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot4b.png)

##### Question 5
- For observing or experiencing a supportive response to mental health at work, the most common responses for all 3 years, 2017, 2018, and 2019, is 'No' followed by 'Maybe/Not sure'. Although if the count results from the options 'Yes, I observed' and 'Yes, I experienced' were combined to 'Yes', then there would be more 'Yes' responses than 'No' for each year. Since the amount of responses for 'Yes, I observed' and 'Yes, I experienced' is fairly similar, it seems as if observing and experiencing support have similar chances of happening in the workplace. Overall, it seems like people have more positive responses to receiving mental health support at work within the last 3 years.]
   - Refer to [Plot 5](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot5.png)
- For observing or experiencing an unsupportive response to mental health at work, the most common responses for all 3 years is still 'No' followed by 'Maybe/Not sure'. Similar to supportive responses, if we combine the count for the two 'Yes' answers,  then there would be slightly more 'Yes' than 'Maybe/Not sure' for each year. There are slightly more counts of observing an unsupportive response than experiencing one. Overall, it seems more mixed on experiencing unsupportive responses to mental health at work. 
   - Refer to [Plot 5b](https://github.com/laimich/Tech-Mental-Health-Survey-Data-Analysis/blob/master/graphs/plot5b.png)
- In comparison, people are more likely to observe or experience a supportive response to mental health than an unsupportive response at work. 
