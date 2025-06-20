# Predicting Productivity from Digital Habits

This repository explores the **impact of digital habits, particularly social media usage, on individual productivity and well-being**. It uses a simulated dataset of 30,000 users to analyze correlations between daily digital behaviors and perceived/actual productivity, stress, and job satisfaction.

### Dataset Overview
**Source:** https://www.kaggle.com/datasets/mahdimashayekhi/social-media-vs-productivity/data
<br>The `social_media_vs_productivity.csv` dataset contains:
* **Digital Habits**: Metrics like daily social media time, number of notifications, and screen time before sleep.
* **Productivity Scores**: Both self-rated (`perceived_productivity_score`) and simulated ground-truth (`actual_productivity_score`).
* **Well-being Indicators**: Stress levels, average sleep hours, days feeling burnout, and job satisfaction scores.
* **Demographics**: Age, gender, and job type of individuals.

| Column Name                     | Description                                                                 |
|---------------------------------|-----------------------------------------------------------------------------|
| `age`                           | Age of the individual (18–65 years)                                         |
| `gender`                        | Gender identity: Male, Female, or Other                                     |
| `job_type`                      | Employment sector or status (IT, Education, Student, etc.)                  |
| `daily_social_media_time`       | Average daily time spent on social media (hours)                            |
| `social_platform_preference`    | Most-used social platform (Instagram, TikTok, Telegram, etc.)               |
| `number_of_notifications`       | Number of mobile/social notifications per day                               |
| `work_hours_per_day`            | Average hours worked each day                                               |
| `perceived_productivity_score`  | Self-rated productivity score (scale: 0–10)                               |
| `actual_productivity_score`     | Simulated ground-truth productivity score (scale: 0–10)                     |
| `stress_level`                  | Current stress level (scale: 1–10)                                          |
| `sleep_hours`                   | Average hours of sleep per night                                            |
| `screen_time_before_sleep`      | Time spent on screens before sleeping (hours)                               |
| `breaks_during_work`            | Number of breaks taken during work hours                                    |
| `uses_focus_apps`               | Whether the user uses digital focus apps (True/False)                       |
| `has_digital_wellbeing_enabled` | Whether Digital Wellbeing is activated (True/False)                         |
| `coffee_consumption_per_day`    | Number of coffee cups consumed per day                                      |
| `days_feeling_burnout_per_month`| Number of burnout days reported per month                                   |
| `weekly_offline_hours`          | Total hours spent offline each week (excluding sleep)                       |
| `job_satisfaction_score`        | Satisfaction with job/life responsibilities (scale: 0–10)                   |
