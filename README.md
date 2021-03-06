# Exploring Mental Health Status for the Elderly in China

### Xin Wei
### Dec 20, 2020

## Background

Since the 20th century, the number and the proportion of the elderly population in China has increased rapidly. From 2000 to 2018, the number of people aged 60 and above increased from 126 million to 249 million. Over the same period, the proportion of the elderly rose from 10.2% to 17.9%, more than twice the world average. Aging is one of the most severe social problems in China in the future. 

A large number of the elderly are suffering from various physical and mental health problems. The number of people that have chronic diseases in China is around 300 million, among which the burden of chronic diseases among people over 65 years old accounts for 50%. Chronic diseases respectively account for 85.3% and 79.5% of the total deaths in urban and rural areas. In this context, finding groups that face different health problems can help better design the healthcare system and deliver health aids to the targeted groups. This project aims to explore what factors may influence the elderly's mental health in China and give some policy insights based on the findings.

## Data Source

This project used the survey data from [CHARLS](http://charls.pku.edu.cn/users/sign_in/en.html)(China Health and Retirement Longitudinal Survey) in 2015 and 2018. All of the data could be download from the official website. Anyone who is interested in the topics of aging and health could request the access of the data from the website organizer. The request may need about one day to be approved. CHARLS data are all released for public, but sometimes the website is inaccessible for some reasons. If you are interested in the topic but cannot download the data, please contact me (*xw256@georgetown.edu*).

CHARLS is a nationwide survey that began to conduct baseline interviews and data collection in 2011 and the subjects were middle-aged and elderly people what were over 45 years old. This dataset covered individual, household and community information including health status and functioning, healthcare and insurance, retirement and pension, personal assets, household assets, household income and history, and so on. After selecting heath related variables and excluding observations with some missing values, I obtained a sample dataset of 16117 subjects in 2015 and 17180 subjects in 2018.

## Visualization Tool
All of the visualizations in this project is made by **Tableau** and are available at **_Tableau Public_**. You can download **_Tableau Public_** from this [link](https://public.tableau.com/) for free.

## Rural vs. Urban 

<p align="center"><iframe seamless frameborder="0" src="https://public.tableau.com/views/PPOL563_Project_final_version/Dashboard1?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '720' height = '540' scrolling='No'></iframe></p>

This visualization is interactive with year. Every point represents the average mental health index and functioning index of a community (each community is randomly selected based on the survey design). Higher mental health or functioning index indicates poorer status. As the Functioning Index increases, people tend to have poorer mental health status. And people in rural areas have poorer mental health status and more functioning problems than those in cities. We can select the subset data of 2015 or 2018. The disparity between the rural and the urban in mental health for the elderly people are similar.

## East vs. West

<p align="center"><iframe seamless frameborder="0" src="https://public.tableau.com/views/PPOL563_Project_final_version/Dashboard2?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '720' height = '540' scrolling='No'></iframe></p>
  
The visualization above has the averages of the Mental Health Index and Functioning Index concerning GDP per capita of each province in China. We can select year 2015 or year 2018 as well. The size of circle represents the scale of GDP per capita of each province. We can see there is a significant disparity between east and west China. The elderly people in Shanghai and Beijing, and Zhejiang, which are the most developed areas in China, have on average the best mental health, while in less developed provinces in the west, mental health problems are much more severe. This also indicates that mental health status in China is still significantly related to economic factors.

## Gender, Education and Mental Health

Women and low-educated people are more likely to develop mental health problems.

<p align="center"><iframe seamless frameborder="0" src="https://public.tableau.com/views/PPOL563_Project_final_version/Dashboard3?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '1100' height = '550' scrolling='No'></iframe></p>

The above visualization shows that females and low-educated people have on average poorer mental health than other groups. We can also select the years, where the results are similar.
  
## Are the elderly people in China satisfied with their life?
  
<p align="center"><iframe seamless frameborder="0" src="https://public.tableau.com/views/PPOL563_Project_final_version/Dashboard4?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '1100' height = '600' scrolling='No'></iframe></p>

The survey has asked questions about whether the subject was satisfied with his/her children, marrirage, health, and the whole life. Similar as the results shown above, females are more likely to show low-level satisfaction of these four questions compared to males. For example, about three quarters of those whose response was 'Not Very Satisfied' were women. You can select the questions and years to examine the results.

## Other Factors: Further Exploration

### _Chronic Diseases_

<p align="center"><iframe seamless frameborder="0" src="https://public.tableau.com/views/PPOL563_Project_final_version/Dashboard6?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '900' height = '580' scrolling='No'></iframe></p>
  
### _Social Activities_
  
<p align="center"><iframe seamless frameborder="0" src="https://public.tableau.com/views/PPOL563_Project_final_version/Dashboard5?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '900' height = '570' scrolling='No'></iframe></p>

This interacitve visualization has pointed out an alarming fact that over one-third of the elderly people in China may be socially isolated (they rarely participate in any social acivities). And a large group of people aged over 50 need to take care of other people (their spouses or children in most cases). This could also have a negative impact on mental health for the elderly people.
  
### _Other Physical Problems: Hearing, Eyesight and Body Pain_

<p align="center"><iframe seamless frameborder="0" src="https://public.tableau.com/views/PPOL563_Project_final_version/Dashboard7?:language=en&:embed=yes&:display_count=yes&:showVizHome=no" width = '1100' height = '550' scrolling='No'></iframe></p> 
  
The bar charts above also indicate that people with the poor hearing capacity and eyesight are more likely to have poor psychological health, compared with those who have very good hearing and vision. Although these problems are not fatal in contrast to other diseases, they are strongly affecting the quality of later life. Different kinds of body pains also have a negative impact on people’s mental health. The average mental health is interactive with year, rural/urban and gender. In each subgroup, we can see the same trend of deteriorative mental health when hearing or eyesight is getting poor or body pain is becoming more serious.
  
## Conclusion

In China, mental health in the elderly is relatively neglected, especially in rural areas. This project used tableau to create several interactive visualizations to explore what factors may affect the elderly’s mental health in China. First, Rural women, usually of low-level education, are one of the groups most suffering from poor mental health. Policymakers should care more about social benefits targeted elderly women in rural areas, especially in west China, helping them self-support their life. Psychological intervention should be considered as well. Second, in findings, physical functioning strongly affects one’s mental health and life quality. In fact, those who suffer from severe physical functioning problem usually need other guardians or support to continue life. However, there is a great supply shortage of professional aged care facilities in China. As a result, most elderly with functioning problems are cared for by their children or relatives. Third, poor eyesight and hearing may have strong negative effects on one’s mental health. Since some severe eyesight and hearing problems could be avoided if they could be diagnosed early and treated with low expenses, the government could introduce special health care insurance targeting eyesight and hearing-related diseases for the elderly.

One limitation of this visualization project is that, it mainly explores mental health status in different groups. It does not include any further analysis using other statistical methods such as regression. Also, based on the nature of survey data, the results may not be very precise and inconsistent between years. For example, we can see there is an apparent increase in mental health problem from 2015 to 2018, but we do not know what this trend means.

  
