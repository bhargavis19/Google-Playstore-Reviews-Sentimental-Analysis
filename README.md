# Google-Playstore-Reviews-Sentimental-Analysis

## Overview
This project aims to analyze user sentiment from reviews of four major social media applications: Instagram, Reddit, Snapchat, and X (formerly Twitter). By examining approximately 40,000 reviews per app, we seek to understand how updates and significant events—such as Elon Musk's acquisition of X—impact user sentiment and engagement.

## Objectives
- Conduct sentiment analysis of Google Play Store reviews to classify user opinions into positive, negative, and neutral categories.
- Identify trends in user feedback related to app updates and major events.
- Evaluate the impact of significant changes on user satisfaction and engagement over time.
- Provide actionable insights for app developers to enhance user experience.

## Dataset Description
The dataset consists of user reviews collected from the Google Play Store for the following applications:
- **Instagram**: 29,600 reviews after cleaning
- **Reddit**: 34,420 reviews after cleaning
- **Snapchat**: 25,783 reviews after cleaning
- **X (formerly Twitter)**: 31,952 reviews after cleaning

Each review includes:
- Review ID
- Review content (text)
- User rating (score)
- App version
- Submission timestamp

## Data Cleaning Process
To ensure the quality of our analysis, we performed the following data cleaning steps:
- **Removal of Duplicate Reviews**: Identified and removed duplicate entries based on review ID and content.
- **Handling Missing Values**: Eliminated rows with missing or incomplete data in critical columns.
- **Final Dataset Sizes**: After cleaning, we retained only essential columns for analysis.

## Exploratory Data Analysis (EDA)
EDA was conducted to understand the structure and distribution of the data. Key findings include:

### User Sentiment Trends:
- Instagram and Reddit show predominantly positive sentiments.
- X exhibits polarized sentiments due to significant changes in ownership and policy.
- Snapchat has a balanced sentiment distribution reflecting mixed user experiences.

### App Version Engagement:
- Review spikes correlate with major updates across all platforms.
- Significant feedback was observed during key events, highlighting user engagement.

## Sentiment Analysis Methodology
We employed natural language processing (NLP) techniques and transformers to classify user sentiments accurately. The analysis was conducted using cleaned datasets to ensure reliable insights.

## Findings
The analysis revealed important trends regarding how platform-specific updates influence user perceptions. Key insights include:
- Instagram's feature rollouts generally received positive feedback.
- Reddit's community-driven model fosters strong user loyalty but faces criticism during controversial changes.
- Changes in X's ownership significantly affected user sentiment, revealing a polarized reception.

## Conclusion
This project provides valuable insights into user sentiment dynamics across popular social media platforms. By analyzing app reviews systematically, we offer actionable recommendations for developers aiming to enhance user satisfaction and engagement.
