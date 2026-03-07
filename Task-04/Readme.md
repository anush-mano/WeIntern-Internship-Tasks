SkillSwap Analytics 📊
Project Overview

SkillSwap Analytics is a Data Science and Analytics module designed to analyze user skill data from the SkillSwap platform. The project identifies skill demand, skill supply, skill gaps, and user skill matching using data analysis and machine learning techniques.

The analysis helps understand which skills are highly demanded and improves skill matching between users.

Objectives

Analyze skills offered and requested by users.

Identify most demanded and most offered skills.

Detect skill gaps in the platform.

Visualize request status distribution.

Implement AI-based skill matching using similarity techniques.

Technologies Used

Python

Pandas – Data loading and processing

Matplotlib – Data visualization

Collections (Counter) – Frequency counting

Scikit-learn – Machine learning algorithms

Algorithms / Techniques Used

Frequency Counting (Counter)

Used to calculate skill demand and supply.

Skill Gap Calculation

Formula:

Skill Gap = Requested Skills − Offered Skills

TF-IDF Vectorization

Converts skill text data into numerical vectors.

Cosine Similarity

Measures similarity between users based on skills.

Dataset

This project uses simulated datasets to represent platform data.

1. users.csv

Contains user information and their skills.

Columns:

user_id

name

skills_offered

skills_requested

2. requests.csv

Contains skill exchange request information.

Columns:

request_id

sender_id

receiver_id

status

3. feedback.csv

Contains feedback information for users.

Columns:

feedback_id

user_id

rating

comments

Project Workflow
1. Data Loading

Load datasets using Pandas.

users = pd.read_csv("users.csv")
requests = pd.read_csv("requests.csv")
feedback = pd.read_csv("feedback.csv")
2. Data Preprocessing

Convert skills to lowercase

Split skills into lists

Remove extra spaces

3. Skill Demand vs Supply Analysis

Use Counter to count frequency of skills offered and requested.

4. Data Visualization

Create bar charts to visualize:

Skill demand vs supply

Request status distribution

5. Skill Gap Analysis

Identify skills where demand is higher than supply.

6. AI-Based Skill Matching

Steps:

Convert skills into text format

Apply TF-IDF Vectorizer

Compute Cosine Similarity

Identify similar users based on skills

Output Insights

The project provides insights such as:

Most demanded skills

Most offered skills

Skills with high demand but low supply

Distribution of request statuses

Similar users for skill exchange

Future Improvements

Integrate with Firebase or real platform database

Implement recommendation system

Build dashboard visualization

Improve matching using advanced ML models

Conclusion

SkillSwap Analytics helps understand skill trends, demand patterns, and user matching within the platform. This analysis can help improve skill exchange efficiency and provide better recommendations to users.
