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

We included these manipulations because we wanted to focus on the boroughs that have the highest freqeuency and concentration of accidents. We also included only the top four causes of collisions to analyze the most common causalities behind injuries and collisions in boroughs where most incidents occur. We filtered the years to only include the most recent year because we wanted to provide analyses that are relevant to the current safety goals of New York City and filtering to the recent year provides a current snapshot of the state of serious collision incidents in New York. These manipulations would give us more insight into common issues that can be prevented with proper safety measures and further analysis.

Question 2 Manipulations:
- Excluded all causes of collisions, except for “Alcohol Involvement”

We included this manipulation because we were analyzing collision incidents that were due to the contributing cause of Alcohol Involvement. By excluding all other causes, we were able to isolate the alcohol involvement variable to see the direct outcomes of collisions due to drunk driving.
# Analysis:
# Tableau Packaged Workbook:
