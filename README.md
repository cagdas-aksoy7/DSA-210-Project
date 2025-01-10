# DSA-210-Project-MANAGE_STRESS_DURING_EXAM_PERIODS
Project Proposal: Analysis of YouTube Usage and Step Count During Exam Periods
⁠ ⁠Introduction (Motivation)

  Academic stress can have a significant impact on daily habits, influencing productivity and  well-being of student. This project explores how my YouTube usage and physical activity, measured through step count, change during exam periods compared to regular times. By identifying these patterns, I aim to understand the effects of academic stress on my behavior and find ways to create healthier habits for better performance. Key questions include: "Does my YouTube usage increase or decrease during exams?" or " Does my content preferences change? "and "How does my physical activity change during high-stress periods?"

# DATA SOURCES


This analysis will use two main sources of personal data:

YouTube Usage Data: Retrieved through Google Takeout, including information on watch history, such as timestamps, video categories, and durations.

Step Count Data: Collected from the Apple Health app, providing daily step counts over several months, covering both exam and non-exam periods.
These sources offer a comprehensive view of my habits, helping to connect changes in behavior to academic stress levels.

# ANALYSIS PLAN



Clean and organize the YouTube watch history to focus on:
Date and time of usage(and maybe also type of content).
Daily watch duration.(Weekly)
Video content types ( educational, entertainment).
Process step count data to calculate:
Daily totals.(exam week period)
Trends over time, especially around exam periods.
Missing or incomplete data will be handled carefully, either through interpolation methods or by excluding unreliable entries to maintain data accuracy.

# EXPLORATORY DATA ANALYSIS (EDA)

Create visuals to show trends in daily YouTube usage and step counts.
Compare averages and patterns during exam periods versus non-exam periods.
Look for unusual spikes or drops in behavior.
This analysis will focus on questions like: "Is there an increase in entertainment content during exams?" or "Do step counts drop significantly due to long study sessions?"

# MODELING AND STATISTICAL ANALYSIS

Use descriptive statistical analysis to summarize YouTube usage and step count data, focusing on averages, medians, and standard deviations to identify patterns.
Compare data from exam and non-exam periods using simple techniques like calculating percentage differences or visualizing trends through charts.
Visualization

Line graphs for time trends.
Boxplots to compare distributions during exam and non-exam times.
Correlation graphs to show possible links between YouTube usage and physical activity.
Additionally, visuals will break down YouTube categories and how their frequency changes during exams, offering a deeper look at content preferences.




# EXPECTED OUTCOMES


Patterns in YouTube usage during exams:
A potential increase in entertainment videos as a way to relax or procrastinate.
A decrease in non-study-related educational content.
Shifts in physical activity:
Lower step counts during intense study days.
Efforts to maintain activity as a way to manage stress.
Personal insights into how stress affects my habits, helping to design better strategies for managing time, stress, and productivity.
The findings could also offer ideas that are useful for others experiencing similar academic pressures.



# IMPLEMENTATION STEPS

Gather and preprocess YouTube and step count data.
Identify exam periods using my academic calendar.
Perform EDA and statistical tests to explore and compare patterns.
Create clear visuals with tools like Matplotlib and Seaborn.
Write a final report summarizing the results and actionable insights.
Python libraries like pandas for data cleaning, matplotlib and seaborn for visuals, and scipy or statsmodels for statistical analysis will be used throughout the project.



This project provides a chance to understand how academic stress affects daily habits like YouTube usage and physical activity. The insights gained can help develop more effective ways to manage time and stress during exams, leading to healthier routines and improved academic performance. By identifying these patterns, I hope to offer practical recommendations that could benefit others facing similar challenges.
