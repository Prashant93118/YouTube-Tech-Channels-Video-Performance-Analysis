# YouTube-Tech-Channels-Video-Performance-Analysis

📌 Project Overview

This project focuses on analyzing tech-focused YouTube channels and their videos to uncover insights related to:

Channel growth patterns

Video performance

Engagement behavior

Content efficiency

The analysis is performed using Python and data analytics techniques, based on real-world scraped YouTube data.

📂 Datasets Used

🔹 Channel Dataset

Contains information about 130 tech YouTube channels, including:

Channel name & ID

Subscriber count

Total views

Total videos

Country

Channel creation date

Shape: (130, 10)

🔹 Video Dataset

Contains data for 1,300 videos, including:

Video title

Views, likes, comments

Video duration (ISO format & seconds)

Channel name & ID

Publish date

Shape: (1300, 14)

🧹 Data Cleaning & Preparation

The following cleaning steps were performed:

Handled missing values in the country column by replacing them with "Unknown"

Converted numeric columns (views, likes, comments, subscribers) to proper numeric types

Converted ISO 8601 video durations (e.g. PT13M43S) into seconds

Cleaned video titles by:

Fixing encoding issues

Removing emojis and special characters

Normalizing extra spaces

Converted date columns to datetime format


📊 Analysis Performed

🔹 Channel-Level Analysis

Top channels by subscribers and total views

Channel with the highest number of uploads

Average subscribers and views per channel

Correlation analysis:

Subscribers vs Total Views (~0.93 – strong correlation)

Total Videos vs Subscribers (~0.26 – weak correlation)

📌 Insight: Uploading more videos does not guarantee subscriber growth.

🔹 Video-Level Analysis

Top 10 videos by views

Top 10 videos by likes

Identification of high-engagement but low-view videos

Distribution analysis of:

Views

Likes

Comments

Average video duration (~30 minutes)

📌 Insight: Long-form educational content performs best in the tech domain.

🔹 Channel Efficiency Analysis

Average views per video per channel

Identification of highly efficient channels (high views with fewer uploads)

📌 Insight: Content efficiency matters more than content volume.

💡 Key Business Insights

Subscriber growth is driven by content quality and relevance, not upload frequency

Educational and tutorial-based content dominates performance

Some smaller creators outperform larger ones in views per video

High-engagement, low-reach videos represent growth opportunities

🛠 Tools & Technologies

Python

Pandas

NumPy

Matplotlib


📄 Project Output

📊 Presentation-ready insights

📈 Visualizations for clear storytelling


🚀 Future Enhancements

Add NLP-based title analysis

Perform time-series upload consistency analysis

Build an interactive dashboard (Power BI / Tableau)

Expand dataset with Shorts vs Long-form comparison

🙌 Author

Prashant
Aspiring Data Analyst | MIS | Business Analytics
Actively building hands-on analytics projects 🚀
