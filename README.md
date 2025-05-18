#  Social-Media-Impact-on-Workplace-Productivity

##  Problem Statement

In today's hyperconnected world, social media has become an integral part of daily life—but its effect on productivity, especially in professional environments, remains a topic of debate. This project explores how variables such as daily social media time, platform preferences, notifications, stress levels, and sleep hours influence both **perceived** and **actual** productivity.

##  Objectives

- Analyze the impact of social media usage patterns on workplace productivity
- Identify key variables that positively or negatively affect productivity scores
- Provide data-driven recommendations for optimizing digital habits
- Explore demographic and professional differences in social media impact

##  Dataset

The dataset contains **30,000 synthetic records** with details related to productivity and social media habits. Key variables include:

- **Age**
- **Gender**
- **Job Type**
- **Daily Social Media Time**
- **Platform Preference**
- **Number of Notifications**
- **Work Hours Per Day**
- **Stress Level**
- **Sleep Hours**
- **Breaks During Work**
- **Use of Focus Apps**
- **Digital Wellbeing Settings**
- **Coffee Consumption**
- **Days Feeling Burnout**
- **Offline Hours**
- **Perceived & Actual Productivity Scores**
- **Job Satisfaction Score**

##  Methodology

1. **Data Cleaning & Preprocessing**
   - Handled missing values using median/mode imputation
   - Removed outliers using IQR method
   - Ensured balanced data across demographics

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix and heatmaps
   - Boxplots and violin plots by gender, job type, and platform
   - Distribution visualizations of screen time and productivity

3. **Insights Extracted**
   - More than 4 hours of daily social media time significantly reduces productivity.
   - Platforms like **Twitter** and **Telegram** correlate with higher productivity.
   - Job types like **IT** and **Finance** show better resilience to digital distractions.
   - High stress and poor sleep drastically reduce productivity, especially in **Health** and **Education** roles.

4. **Recommendations**
   - Limit social media to **2–3 hours** daily
   - Use productivity-friendly platforms (e.g., Twitter)
   - Minimize unnecessary notifications
   - Use **focus apps** (like Forest) and enable **digital wellbeing** settings
   - Maintain **6–8 hours of sleep** and adopt **structured daily routines**

##  Key Visualizations

- Correlation Heatmap
- Productivity by Job Type
- Average Productivity by Platform
- Gender-wise Productivity Distributions
- Daily Social Media Time Distributions
- Stress vs Productivity Scatterplots
- Pairplots of critical variables

##  Project Structure

```bash
├── data/
│   └── social_media_vs_productivity.csv
├── images/
│   └── visualizations.png (optional)
├── social_media_vs_productivity.ipynb
└── README.md
