# Screen Time & Mental Wellbeing 


## 1. Dataset
- Source: https://www.kaggle.com/datasets/adharshinikumar/screentime-vs-mentalwellness-survey-2025/data
- Downloaded zip file of data from kaggle and extracted it into the project folder.
- This dataset captures insights from 400 survey participants on how their daily screen usage relates to mental wellness. With the growing prevalence of digital devices in our lives, understanding the link between screen time, sleep quality, stress, and productivity is a crucial research area for data science, psychology, and public health. Each row represents one survey participant and contains information on the following columns

**age** - Age of the participant (in years).

**gender** - Gender of the participant (Male, Female, Other).

**occupation** - Participant’s role (Student, Working Professional, Freelancer, etc.).

**work_mode** - Work/study mode (Remote, On-site, Hybrid).

**screen_time_hours** - Total average daily screen usage (hours).

**work_screen_hours** - Daily screen time spent on work/study tasks (hours).

**leisure_screen_hours** - Daily screen time spent on leisure (social media, streaming, gaming).

**sleep_hours** - Average sleep duration per night (hours).

**sleep_quality_1_5** - Self-reported sleep quality rating (1 = very poor, 5 = excellent).

**stress_level_0_10** - Self-reported stress level (0 = no stress, 10 = extremely stressed).

**productivity_0_100** - Self-rated productivity score (0–100).

**exercise_minutes_per_week** - Total minutes spent exercising in a week.

**social_hours_per_week** - Hours spent socializing offline per week.

**mental_wellness_index_0_100** - Composite index reflecting overall wellness (0–100).



**Note** - Certain columns, such as "stress_level_0_10" and "productivity_0_100"  are named as 0-10, or 0-100 rating, however they are float values. It is understood that there are from interactive sliding scale response trackers and are treated as such.  

## 2. Objectives
- Clean and prepare a raw dataset containing demographic, lifestyle, and wellness data.

- Explore relationships between variables such as sleep duration, screen time, stress, and mental wellness index.

- Identify potential behavioral or occupational factors influencing wellness.

- Communicate insights clearly through visualizations and concise interpretation.

## 3. Methodology
- **ETL (Extract, Transform, Load)**
- Loaded dataset into a pandas DataFrame.
- Checked for missing values, duplicates and removed extraneous columns.

- **Exploratory Analysis**
- Summary statistics for wellness and lifestyle metrics.
- Correlation analysis and scatter plots to examine relationships.
- Grouped comparisons

- **Feature Engineering**
- Created new columns such as 'sleep_efficiency', 'weekly_wellness_behaviour_hours', 'sleep_efficiency_group', and 'stress_level_0_100' to aid in visualisation and better understand the data

- **Visualisation**
- Seaborn scatterplots and regression lines for key variable relationships.
- Grouped bar charts using Plotly for mean comparisons.

- **Machine Learning**
- Created a regression model with selected and engineered features to predict wellness outcomes.

## 4. Findings and Conclusions

- The quality and duration of sleep was the highest predictor of high mental wellness scores and lower stress levels.

- More time spent on screens, especially leisure screen time, was a predictor of lower mental wellness.

- Occupation status of employed and student showed highest screen use times and lowest mental wellness

- Occupation status of unemployed and retired showed lowest screen usage and highest mental wellness.

- Overall, adequate, good-quality sleep appears to be the key protective factor for mental wellness, while higher screen exposure—especially during leisure—relates to poorer outcomes.

## 5. Tools
- JupyterLab through Anaconda Navigator for writing code.

- Python 3

- pandas – Data cleaning, transformation, and aggregation

- matplotlib / seaborn – Static visualizations and subplots

- plotly.express – Interactive visualizations

- numpy – Numerical processing

- ScikitLearn - Machine Learning

- ChatGPT - Coding assistance & guiding in project direction

## 6. Credits
- Thanks to John Anih at CodeInstitute for his teaching of the Data Analytics with AI Bootcamp


