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

•	Identifying daily trends in screen time for both platforms to understand patterns in engagement.

•	Investigate whether Linkedin usage peaks during job search periods, such as days when job applications are submitted, to understand if professional activity increases during these times. 

•	Investigate whether TikTok or Linkedin usage peaks during academic stress periods (e.g., exam days) or during relaxation periods (days without exams and job applications) to understand whether entertainment is used more as a stress-relief tool or during free time.

## 3. Correlation Analysis
This phase will investigate the relationship between Linkedin and TikTok usage (Pearson Correlation):

•	Investigating whether increased Linkedin screen time correlates with decreased TikTok usage (or vice versa).
•	Identifying whether TikTok screen time is negatively correlated with academic event days (exam period)
•	Identifying whether Linkedin screen time is negatively correlated with academic event days (exam period)
• Identifying the correlation between Linkedin screen time and job application counts in order to investigate whether professional engagement (i.e., time spent on Linkedin) peaks during active job search days.
•	Calculating correlation coefficients to measure the strength and direction of the relationship between Linkedin and TikTok usage over time.

## 4. Visualization
To help visualize the trends and relationships, several types of charts will be created:

• Heat Map:
In this heatmap analysis, we aim to visually explore how screen time usage varies across different types of days (Exam Day, Job Application Day, No Event) and time of day (Morning, Evening, Night) for both TikTok and LinkedIn.
These visualizations will offer both high-level patterns and nuanced insights into how and when each platform is used, and how that usage may relate to academic or professional demands

• Scatter Plots:
- LinkedIn Screen Time vs. TikTok Screen Time: This scatter plot will visualize the relationship between TikTok and Linkedin screen time to see if increased entertainment usage on TikTok correlates with reduced professional engagement on Linkedin (or vice versa).
  
- Linkedin Screen Time vs. Jobs Applied: This scatter plot will examine whether higher Linkedin screen time is associated with a greater number of job applications, indicating that increased Linkedin engagement supports job-seeking activity.

- TikTok Screen Time vs. Exam Days (Academic Events): This scatter plot will explore if TikTok screen time increases during exam days, suggesting that TikTok may be used as a stress-relief mechanism during academic pressure periods.

- Linkedin Screen Time vs. Exam Days (Academic Events): This scatter plot will analyze how Linkedin screen time changes during exam days, helping to determine whether academic stress reduces professional engagement or if Linkedin usage increases due to job search priorities during exams.

•	Bar charts:
- Identify peak usage days for each platform and also to compare average screen time on different types of days (e.g., job application days, exam days, and non-event days).
- Visualize the average screen time across different times of the day, allowing us to observe which time periods users tend to engage most with TikTok and Linkedin.

• Box Plots:
To compare TikTok and Linkedin screen time distributions across different contextual periods:
 – Exam Periods
 – Job Search Days
 – Non-Event Days
This will help assess whether TikTok and Linkedin usage increases on low-pressure days (like non-event days) and decreases during high-pressure periods (like exams), indicating a potential coping mechanism.


## 5. Hypothesis Testing

•	Statistical tests will be used to validate the hypothesis that increased time spent on TikTok correlates with reduced Linkedin usage, and vice versa. We will test whether there is a significant relationship between them.

•	Secondly, we will test whether Linkedin usage increases during job search periods (with a focus on employment-related tasks) and whether TikTok usage is higher during non-exam or low-academic-stress periods.

•	Thirdly,  we will test whether TikTok and uLinkedin sage increases on days without academic stress (non-exam periods).

•	Lastly, we will test whether Linkedin usage increases during job application days. (The amount of time spent on LinkedIn is higher on job application days compared to days when no job applications are made.)


## 6. Conclusion
At the conclusion of this analysis:

•	A summary of findings will be provided and it will also discuss how balancing professional engagement with entertainment impacts productivity, stress levels, and overall time management, offering insights on how students and job-seekers can optimize their use of both platforms during critical phases of their academic and career journey.








