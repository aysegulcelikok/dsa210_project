## DSA 210 PROJECT AYŞEGÜL ÇELİKOK
## Motivation
As a final-year university student, balancing my professional responsibilities and entertainment time is crucial for me. I use Linkedin  as a platform for job search and networking. On the other hand, I use TikTok for entertainment. With graduation approaching, my Linkedin usage is expected to increase as I actively look for job opportunities. At the same time, TikTok, known for its addictive short-form content, might act as a distraction, reducing the time I spend on my career via Linkedin.

By analyzing my screen time data over one year, I aim to:

Understand whether higher Linkedin usage correlates with reduced TikTok engagement, or vice versa and determining if one platform's increased usage directly affects the time spent on the other.

Identify daily trends—for example, whether TikTok or Linkedin usage peaks during no exam or exam periods during that day or Linkedin usage and job application number peaks during job application periods.

 
## Project Goal
The goal of this project is to analyze how my screen time on Linkedin and TikTok fluctuates throughout my final year. By tracking daily usage data, I will explore whether professional engagement on Linkedin and entertainment-driven TikTok usage influence each other. This project will enable me to understand how to better manage and spend my time thus to stay focused during the important job search period.


## Data Description
The dataset comprise daily screen time data for Linkedin and TikTok over one year and includes the following columns:

Date: The specific calendar day.

LinkedIn_ScreenTime (minutes): The total time spent on LinkedIn on that day.

TikTok_ScreenTime (minutes): The total time spent on TikTok on that day.

Day_Type: Whether the day is a "Weekday" or "Weekend".

Academic_Events: Indicates whether a significant academic event (e.g., exam) occurred on that day. Values are "Exam" or "None".

Time_of_Day_Used: The general time of day when the platforms were accessed — values like "Morning", "Afternoon","Evening", "Night".

Jobs_Applied_Count: Number of job applications submitted via LinkedIn on that day.

#Note: Since I typically access both LinkedIn and TikTok only once per day, the dataset records daily totals rather than multiple time intervals.

## Data Analysis
## 1. Data Preprocessing
In this phase, the following steps will be taken to ensure the data is clean and ready for analysis:

•	Cleaning and structuring the daily screen time data for Linkedin and TikTok. This includes identifying inconsistencies or missing data. Moreover ensuring time data is standardized (in minutes).

•	Standardizing time units for consistency, such as controlling all data is in minutes per day.

•	Aligning timestamps to ensure Linkedin and TikTok data can be compared across different days, allowing us to identify trends in usage.

•	Since the platforms are accessed only once per day, the dataset reflects total daily screen time.

## 2. Exploratory Data Analysis (EDA)
This phase will involve analyzing the overall trends in the usage of Linkedin and TikTok:

•	Identifying daily trends in screen time for both platforms on weekday and weekends to understand patterns in engagement.

•	Investigate whether Linkedin usage peaks during job search periods, such as days when job applications are submitted, to understand if professional activity increases during these times. 

•	Investigate whether TikTok or Linkedin usage peaks during academic stress periods (e.g., exam days) or during relaxation periods (days without exams and job applications) to understand whether entertainment is used more as a stress-relief tool or during free time.

## 3. Correlation Analysis
This phase will investigate the relationship between Linkedin and TikTok usage (Pearson Correlation):

•	Investigating whether increased Linkedin screen time correlates with decreased TikTok usage (or vice versa).

•	Identifying whether TikTok screen time is negatively correlated with academic event days (exam period)

•	Identifying whether Linkedin screen time is negatively correlated with academic event days (exam period)

• Identifying the correlation between Linkedin screen time and job application counts in order to investigate whether professional engagement (i.e., time spent on Linkedin) peaks during active job search days.

• Investigate if Linkedin screen time increases over the academic year, particularly as graduation approaches

• Investigate if TikTok screen time decreases over the academic year, indicating a possible shift from entertainment to career focus 

•	Calculating correlation coefficients to measure the strength and direction of the relationship between Linkedin and TikTok usage over time.
• Pearson correlation coefficients (r) to measure the strength and direction of the relationships.
## 4. Visualization
• Pie Chart

- The number of job applications submitted during the exam period and non-exam days (days with no significant academic events)

• Heat Map:
To compare the average screen time spent on TikTok and Linkedin depending on the day type (e.g., weekday or weekend) and the time of day the platforms were used

- When TikTok or Linkedin is used most often during the day.

- Whether usage patterns differ between weekdays and weekends.

- Which platform dominates attention during specific time slots

•	Bar charts:

- Total number of job applications submitted on weekdays versus weekends
- Identify peak usage days for each platform and also to compare average screen time on different types of days (e.g., job application days, exam days, and non-event days).
- Visualize the average screen time across different times of the day, allowing us to observe which time periods users tend to engage most with TikTok and Linkedin.

• Box Plots:

To compare TikTok and Linkedin screen time distributions across different contextual periods:
 – Exam Periods
 – Job Search Days
 – Non-Event Days
This will help assess whether TikTok and Linkedin usage increases on low-pressure days (like non-event days) and decreases during high-pressure periods (like exams), indicating a potential coping mechanism.

• Line Chart:

- To identify how screen time on Linkedin and TikTok changes over time.
  
## 5. Hypothesis Testing

H1: Linkedin usage is more likely to occur during working hours (morning to early afternoon), reflecting a professional engagement pattern aligned with standard workday routines.

H2: TikTok screen time peaks during the night, especially on weekends, indicating increased entertainment-driven usage during leisure periods.

H3: Linkedin usage increases over the final academic year, particularly as graduation approaches, due to heightened job search and career preparation activity.

H4: TikTok usage decreases over the final academic year, particularly as graduation approaches, as users may shift focus away from entertainment.

H5: Linkedin screen time is significantly higher on job application days compared to days when no job applications are made, indicating a focused effort on career-related tasks.

H6: Linkedin screen time decreases during exam periods, suggesting reduced professional platform engagement due to academic workload.

H7: TikTok screen time decreases during exam periods, suggesting a decline in entertainment use under academic pressure.

H8: Increased time spent on TikTok negatively correlates with LinkedIn usage, and vice versa — meaning when one platform’s usage goes up, the other tends to go down.

# 6. Conclusion
At the conclusion of this analysis:

•	A summary of findings will be provided and it will also discuss how balancing professional engagement with entertainment impacts productivity, stress levels, and overall time management, offering insights on how students and job-seekers can optimize their use of both platforms during critical phases of their academic and career journey.








