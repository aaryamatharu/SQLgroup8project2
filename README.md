# Team 8 Mist 4610 Group Project 2
# Team Name:
4610 Fa24 Group8
# Team Members:
1. Aarya Matharu [@aaryamatharu](https://www.github.com/aaryamatharu)
2. Anica Singh [@anicasingh](https://www.github.com/anicasingh)
3. Murray Freedman [@murrayfreedman](https://www.github.com/murrayfreedman)
4. Nick Dortzbach [@dortzenbacher](https://www.github.com/dortzenbacher)
5. Jonah Kilpi [@Jonah-Kilpi](https://www.github.com/Jonah-Kilpi)
# Data Set:
This data set was obtained from the US Data Government Website, and the publisher of the dataset is The City of New York. This dataset is a record of traffic crashes, including details like crash date, time, location, and contributing factors. The Motor Vehicle Collisions data tables contain information from all police-reported motor vehicle collisions in NYC. The police report (MV104-AN) is required to be filled out for collisions where someone is injured or killed, or where there is at least $1000 worth of damage and provides data that could be used for traffic safety analysis. This dataset could be used to analyze trends in traffic accidents, identify high-risk locations, and inform safety measures.

<img width="570" alt="Screenshot 2024-11-21 at 2 46 10 PM" src="https://github.com/user-attachments/assets/6646a8e4-7805-41cf-9630-ea3374418e5b">

# Questions:
**1. In 2023, what was the total number of collisions that occurred during each hour of the day across the boroughs with the 3 highest number of collisions, and how did this distribution differ for the causes of driver inattention, backing unsafely, failure to yield the right-of-way, and following too closely?**

Importance: Understanding the hourly distribution of collisions can inform targeted interventions such as deploying traffic enforcement or awareness campaigns during high-risk hours. Examining specific causes—driver inattention, backing unsafely, failure to yield, and following too closely—helps identify behavioral patterns that lead to collisions, enabling borough-specific and cause-specific safety strategies. This is socially significant as it can reduce injuries, fatalities, and economic losses caused by preventable crashes.


**2. Is there a statistically significant correlation between the time of day and the likelihood of "drunk driving" being a contributing factor in crashes, with a particular focus on nighttime hours?**

Importance: Drunk driving is a major public safety concern, often linked to nighttime hours. Analyzing whether there is a statistically significant correlation between time of day and drunk driving likelihood can guide law enforcement and public health efforts, such as the timing of DUI checkpoints or awareness campaigns. Addressing this issue is culturally critical to reducing the stigma around drunk driving and improving roadway safety for all.

# Manipulations:
General: 
- We excluded the "null" borough. 
- We also excluded the “Null”, “1”, “80”, and “Unspecified” contributing causes.

These manipulations were made because they were unclear on their meaning and were overall irrelevant to the analyses that we were aiming to conduct. Having these included in our analyses would unnecessarily overpopulate the data and distract from the relevant results we are trying to analyze.

Question 1 Manipulations:
- Included only the boroughs with the three highest numbers of collision
- Included only the top four causes of collisions
- Filtered the years, so we can just focus on the trends of the most recent year

We included these manipulations because we wanted to focus on the boroughs that have the highest frequency and concentration of accidents. We also included only the top four causes of collisions to analyze the most common causalities behind injuries and collisions in boroughs where most incidents occur. We filtered the years to only include the most recent year because we wanted to provide analyses that are relevant to the current safety goals of New York City and filtering to the recent year provides a current snapshot of the state of serious collision incidents in New York. These manipulations would give us more insight into common issues that can be prevented with proper safety measures and further analysis.

Question 2 Manipulations:
- Excluded all causes of collisions, except for “Alcohol Involvement”

We included this manipulation because we were analyzing collision incidents that were due to the contributing cause of Alcohol Involvement. By excluding all other causes, we were able to isolate the alcohol involvement variable to see the direct outcomes of collisions due to drunk driving.
# Analysis:
**Question 1:**
The analysis of collision trends by time of day reveals that there are relatively few collisions between 12 AM and 5 AM, with the number of collisions steadily increasing throughout the day. The peak occurs around 3-5 PM, followed by a steady decline in collisions after 5 PM. Comparing boroughs, Manhattan consistently experiences fewer collisions than Queens and Brooklyn, which see higher incident rates. In terms of distracted driving, Brooklyn stands out with significantly more collisions throughout most of the day, particularly between 5-8 AM. This increase during the morning hours is likely driven by the high volume of commuters heading to work. These trends highlight the need for targeted interventions during peak hours and in high-risk boroughs, particularly Brooklyn. The data and analysis provide valuable insights that can help law enforcement and traffic safety organizations better allocate resources during peak collision times, particularly in high-risk areas like Brooklyn. By identifying patterns in distracted driving, especially during morning commutes, authorities can implement more effective prevention strategies, such as increased patrols or targeted public awareness campaigns. This proactive approach will not only help reduce collisions but also improve overall traffic safety for commuters and pedestrians. Additionally, understanding these trends can guide the development of smarter traffic infrastructure and policies to address the root causes of accidents. These efforts are crucial for creating safer, more efficient roadways in the future.
**Question 2: **
The p-value analysis shows a significant relationship between crash time and the number of alcohol-involved crashes, with a p-value of less than 0.0001. The r-squared value of 0.893852 indicates that time of day accounts for a high percentage of the variability in crash frequency. Crash time trends reveal a clear peak during late night and early morning hours, which aligns with higher rates of drunk driving incidents. This suggests that alcohol-related crashes are more likely to occur during these times, potentially due to impaired judgment associated with late-night activities. The data strongly supports a correlation between drunk driving and nighttime crashes in NYC. These findings highlight the importance of targeted interventions, such as increased DUI checkpoints or awareness campaigns, during these high-risk hours. This data and analysis are crucial for law enforcement and traffic safety agencies to strategically plan and deploy resources during high-risk hours, such as late-night and early morning, when alcohol-related crashes peak. By identifying these patterns, authorities can implement more targeted prevention measures, such as increased DUI checkpoints, breathalyzer tests, and public awareness campaigns, to reduce alcohol-related incidents. Additionally, the analysis could guide the placement of traffic safety infrastructure, such as improved lighting or signage, in areas most prone to nighttime crashes. 

# Tableau Packaged Workbook:



