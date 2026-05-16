## CFPB Consumer Complaint Analysis
### Project Overview

This project analyzes over 14 million consumer complaints submitted to the Consumer Financial Protection Bureau (CFPB) against financial institutions across the United States.
The goal of the project is to explore:
- Why consumers file complaints
- Which financial products generate the most issues
- How complaint behavior differs across users
- What complaint narratives reveal about customer dissatisfaction

The analysis combines:
- Exploratory Data Analysis (EDA)
- Behavioral Segmentation
- Natural Language Processing (NLP)
- Sentiment Analysis
- Data Visualization
to uncover patterns within large-scale financial complaint data.

### Problem Statement

Financial institutions receive millions of customer complaints every year, but complaint volume alone does not explain the underlying behavioral and operational patterns driving dissatisfaction.
This project investigates:
> What are consumers complaining about, how do complaint behaviors differ, and what themes consistently appear across complaint narratives?

### Dataset Information
**Source**
Consumer Financial Protection Bureau (CFPB) Consumer Complaint Database

**Dataset Characteristics**
- 14M+ complaint records
- Real-world messy data
- Free-text complaint narratives
- Missing values
- Inconsistent labels
- Multiple financial product categories

**Key Columns**
- Product
- Sub-product
- Issue
- Sub-issue
- Consumer Complaint Narrative
- Company
- State
- Timely Response
- Consumer Disputed
- Company Response

### Tools & Technologies
- Python
- Pandas
- Matplotlib
- NLP & Text Analysis
- Jupyter Notebook

### Data Cleaning & Preparation

The following preprocessing steps were performed:
- handled missing values strategically
- standardized product categories
- removed duplicates
- engineered behavioral flags
- cleaned complaint narratives
- removed irrelevant text noise and placeholders
- prepared text data for NLP analysis

### Exploratory Data Analysis (EDA)

The analysis explored:
- complaint volume trends over time
- top complaint categories
- top companies receiving complaints
- issue frequency distribution
- operational response patterns

**Key Findings**
- Credit-related complaints dominate the dataset
- Investigation and dispute issues appear repeatedly
- Complaint volumes have grown significantly over time
- Timely response rates remain consistently high

### Behavioral Segmentation

Complaints were grouped into behavioral segments to understand customer engagement patterns.
- Segments Created
- High Engagement Complaints
- Low Engagement Complaints
- System-Driven Credit Complaints
- Other Complaints
**Key Insight**
A large portion of complaints fall into repetitive credit-related complaint behavior patterns, suggesting recurring structural issues within reporting and dispute systems.

### NLP & Sentiment Analysis

Natural Language Processing techniques were applied to complaint narratives.
Analysis Included
- text preprocessing
- word frequency analysis
- word cloud visualization
- sentiment analysis

**Common Narrative Themes**
- credit reporting
- inaccurate information
- debt
- payment disputes
- account management

### Future Improvements
- Advanced NLP topic modeling
- Machine learning classification
- Interactive dashboard enhancements
- Time-series forecasting
