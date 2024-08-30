README: How to Use the Social Media Analysis Code
Overview

This repository contains code for analyzing consumer perceptions and brand engagement related to Fiat Dolcevita and Mini Cooper in the UK market. The analysis primarily focuses on understanding public sentiment, identifying key topics of discussion, and comparing the branding effectiveness of Fiat Dolcevita with its competitor, Mini Cooper. The project includes several key analyses, each targeting different aspects of the social media landscape.

Project Structure

Data Collection and Analysis
Instagram Analysis (Insta_Analysis.ipynb)
YouTube Analysis (YouTube_Analysis.ipynb)
Mini Cooper Analysis (Mini_Cooper_Analysis.ipynb)
Secondary Analysis Using Collected Data
Competitor Analysis (Competitor_Analysis.ipynb)
Opinion Leader Analysis (Opinion_Leader_Analysis.ipynb)
Engagement Analysis (Engagement_Analysis.ipynb)
Code Files and Their Usage

Instagram Analysis (Insta_Analysis.ipynb)
Purpose: Collects and analyzes comments from Instagram related to Fiat Dolcevita. The analysis includes data preprocessing, topic modeling, and sentiment analysis to uncover public perceptions on this platform.
Data Files: This notebook has data collection steps and uses Instagram data scraped using APIs.
How to Use:
Run the notebook to collect and preprocess data.
Perform topic modeling to identify key themes.
Conduct sentiment analysis to gauge public opinion.
YouTube Analysis (YouTube_Analysis.ipynb)
Purpose: Similar to the Instagram analysis but focuses on YouTube comments. This notebook aims to understand how Fiat Dolcevita is perceived on a platform known for more detailed, long-form content.
Data Files: The data is collected directly within the notebook using YouTube’s API.
How to Use:
Execute the data collection steps to gather YouTube comments.
Run topic modeling and sentiment analysis to extract insights.
Review the results to understand public sentiment and key discussion topics.
Mini Cooper Analysis (Mini_Cooper_Analysis.ipynb)
Purpose: Focuses exclusively on Mini Cooper, using the same methodologies applied to Fiat Dolcevita. This allows for a direct comparison between the two brands.
Data Files: Includes data collection steps similar to the Instagram and YouTube analyses.
How to Use:
Gather and preprocess Mini Cooper data.
Perform topic modeling and sentiment analysis to uncover the brand's perception.
Compare these insights with those from the Fiat Dolcevita analysis.
Competitor Analysis (Competitor_Analysis.ipynb)
Purpose: Compares Fiat Dolcevita with Mini Cooper using the data collected from the Instagram, YouTube, and Mini Cooper analyses. The focus is on understanding competitive positioning.
Data Files: Utilizes the datasets gathered from the other analysis notebooks.
How to Use:
No new data collection is required. Use the pre-collected data.
Execute the comparative analysis to highlight differences in consumer sentiment and topic emphasis.
Review the results to identify strengths and weaknesses relative to the competitor.
Opinion Leader Analysis (Opinion_Leader_Analysis.ipynb)
Purpose: Analyzes the impact of key opinion leaders on the perception of Fiat Dolcevita. This notebook examines how influential figures shape public opinion.
Data Files: Relies on the data collected from the Instagram and YouTube analyses.
How to Use:
Utilize the pre-processed data from earlier notebooks.
Identify and analyze the role of opinion leaders in shaping brand perception.
Interpret the results to understand the influence dynamics.
Engagement Analysis (Engagement_Analysis.ipynb)
Purpose: Evaluates engagement metrics like comments, likes, and sentiment scores over time, providing insights into the brand’s digital presence and interaction levels.
Data Files: Uses data from the Instagram, YouTube, and Mini Cooper analyses.
How to Use:
Use the already collected data from the other analyses.
Analyze engagement metrics to understand consumer interaction patterns.
Visualize the results to identify key trends in engagement.
Methodology

Each analysis involves the following key components:

Data Collection: Data is gathered from Instagram and YouTube using APIs or scrapers, focusing on user-generated content about Fiat Dolcevita and Mini Cooper.
Data Preprocessing: Includes cleaning, tokenization, stopword removal, and translation (if necessary).
Topic Modeling: LDA (Latent Dirichlet Allocation) is used to identify key topics and themes within the data.
Sentiment Analysis: VADER is applied to determine the sentiment of the collected comments.
Summarization: A BART-based model is used to summarize the identified topics and themes, providing concise overviews of public discussions.
Results

The analyses reveal both positive and negative sentiments toward Fiat Dolcevita, with key strengths in design and urban practicality, and challenges in technical performance and cost perception. The comparative analysis with Mini Cooper highlights areas for improvement in Fiat's branding strategy, particularly in addressing public concerns and aligning marketing messages with consumer expectations.

