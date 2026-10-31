**Social media and mental health: a possible link.**

**A case of interest for the U.S. Department of Education.**

**Context**

The U.S. Department of Education has recently expressed concern about the potential effects of excessive social media use on students’ mental health. To investigate, they sponsored a study of high school, undergraduate, and graduate students aged 18–24 living in the U.S. for more than 10 years, from diverse countries of origin.

**Research Question**

How does daily time spent on social networks relate to mental health scores among students, and does the relationship vary across students' ages? 

**Dataset** 

You are provided with the dataset: **[Students_Social_Media_Add_V2.csv](https://purdue.brightspace.com/content/enforced/1643018-wl.202710.QM.57100.DY1/Students_Social_Media_Add_V2.csv)**

The data dictionary is shown below:

|**VARIABLE**|**DESCRIPTION**|
|---|---|
|**Student_ID**|A unique identifier assigned to each respondent, used for de-duplication without revealing personal information.|
|**Age**|The student’s age in completed years at the time of the survey.|
|**Gender**|The student’s self-reported gender, recorded as “Male” or “Female”.|
|**Academic_Level**|The highest level of education the respondent is currently enrolled in, with categories: “High School,” “Undergraduate,” or “Graduate”.|
|**Country**|The country of birth of the student.|
|**Avg_Daily_Usage_Hours**|The average number of hours per day the student spends on social media platforms, calculated from self-reported weekday and weekend usage estimates.|
|**Most_Used_Platform**|The social media platform on which the student spends the most time (e.g., Instagram, Facebook, TikTok).|
|**Affects_Academic_Performance**|A binary indicator (“Yes”/“No”) reflecting whether the student perceives their social media use as having a negative impact on their academic performance.|
|**Sleep_Hours_Per_Night**|The respondent’s average nightly sleep duration in hours.|
|**Mental_Health_Score**|A self-rated integer from 1 (poor) to 10 (excellent) indicating overall mental well-being.|
|**Relationship_Status**|The student’s current romantic relationship status, categorized as “Single,” “In Relationship,” or “Complicated”.|
|**Conflicts_Over_Social_Media**|The number of arguments or disagreements the student reports having had with family, friends, or partners due to their social media use.|
|**Addicted_Score**|A composite score from 1 (low addiction) to 10 (high addiction) based on a standardized survey scale (e.g., Bergen Social Media Addiction Scale).|

**What to do**

1. **Understand the research question**: What does it require? What does it aim to discover?
2. **Explore the provided dataset** and **implement appropriate corrections and imputations** to prepare it for analysis. Specifically, look for, detect, and treat outliers and null values.
3. **Select the appropriate variables needed to address the research question.**
4. **Create at least four charts that clearly provide evidence to answer the question. Remember:**

5. Consider the types of variables you selected from the dataset when choosing the proper type of chart to show insights (based on the content reviewed in the lessons).
6. Use these visualizations to build a dashboard that supports decision-making
7. You must program and obtain your charts using **Python** or **Orange Data Mining.**

8. **Interpret the plots/dashboard** constructed for answering the Research question:

a. Respond succinctly: one paragraph summarizing your findings in plain terms. 

**Deliverable**

One executive slide deck (9 slides), submitted in **PDF** format, following this structure:

1. **Cover Page.** Include title, submission date, and name of student.
2. **Introduction**: Case background, Department of Education sponsorship.
3. **Summary of the corrections and imputations applied** to prepare the dataset for analysis. Justify all actions taken.
4. **Research Question to respond to.**
5. **Variables used in the analysis**.  Describe the variables chosen and why.
6. **Your Visualizations implemented in a dashboard**. Insert your dashboard, with at least four charts, in one slide.
7. **Your Interpretation.** One clear, concise paragraph answering the question.

**Additional suggestions**

1. Use **Python** or **Orange Data Mining** for coding and/or creating your charts. 
2. If you use the Plotly library, verify that it is installed on your computer.