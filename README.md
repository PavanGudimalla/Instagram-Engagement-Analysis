# 📱 Digital Media Optimization: Predictive Analytics for Social Engagement

## 🎯 Executive Summary
In the highly competitive landscape of digital media planning and advertising operations, understanding algorithmic content drivers is critical for ROI. This project utilizes web scraping, natural language processing (NLP), and predictive modeling to decode the engagement mechanics of a commercial Instagram account ("Old City Foodies"). By translating statistical findings into an optimization engine, this project delivers a data-backed blueprint for maximizing social media reach and audience engagement.

## 🛠️ Methodology & Technical Execution
* **Data Acquisition:** Scraped live production data using Apify to build a custom dataset containing engagement metrics, metadata, and post captions.
* **Statistical Modeling:** Engineered multiple Ordinary Least Squares (OLS) regression models, applying natural log transformations and interaction terms to accurately predict engagement volume (likes) while controlling for outliers.
* **Sentiment Analysis:** Deployed R packages (`sentimentr`, `textdata`) to quantify the emotional polarity of post captions.
* **Operations Research:** Built an optimization framework using Excel Solver to maximize predicted engagement under realistic operational constraints (e.g., hashtag limits).

## 📊 Key Findings & Algorithm Decoding
* **The Video Imperative:** Regression coefficients overwhelmingly proved that video plays are the single strongest driver of engagement, far outpacing caption length or static image dimensions.
* **Hashtag Elasticity:** Identified a strong positive correlation between hashtag volume and reach, up to an optimized threshold.
* **The Comment Paradox:** Discovered a negative correlation between high comment volume and likes, identifying potential algorithmic penalties associated with spam or controversial content.
* **Sentiment Impact:** While strict log-modeling favored quantitative metrics, exploratory analysis showed posts with positive sentiment averaged significantly higher baseline engagement (1,798 average likes vs. 358 for neutral).

## 💡 Impact for Media Planning & Ad Operations
This project acts as a direct portfolio piece for **Media Planners and Marketing Analysts**. It moves beyond vanity metrics by using statistical rigor to inform content strategy. By integrating the regression outputs into an Excel Solver model, I created a tactical tool that dictates exactly how resources should be allocated (e.g., capping hashtags at 30, prioritizing video production over copywriting) to achieve a guaranteed engagement baseline.
