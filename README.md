# 📊 Analyzing Online Campaign Performance: KitKat's "Snap to Decide" Digital Campaign

<p align="center">

**A Data-Driven Analysis of Social Media Engagement, Brand Awareness & Purchase Intent**

</p>

---

## 📌 Project Overview

This project presents a data-driven analysis of KitKat's **"Snap to Decide" Instagram campaign**, designed to understand how social media interactions translate into brand awareness, customer engagement, sentiment, and purchase intention.

The study analyzed **19,461 Instagram comments** collected from KitKat India's campaign posts and applied Python-based Natural Language Processing (NLP), keyword analysis, sentiment analysis, purchase-intent classification, engagement scoring, and time-series analysis.

The research was published in the **International Journal of Advanced Research in Science, Communication and Technology (IJARSCT)** in May 2026. 

---

## 🎯 Objectives

The project focuses on four major objectives:

* Analyze the effectiveness of the KitKat "Snap to Decide" campaign in terms of user engagement and brand awareness.
* Evaluate the relationship between online interactions and purchase intent.
* Identify suitable measures for evaluating digital campaign success.
* Measure campaign performance using Instagram user engagement data. 

---

## 🔍 Key Research Questions

* How effectively did the campaign generate brand awareness?
* What level of purchase intention was expressed by users?
* Does higher engagement translate into stronger purchase intent?
* What sentiment patterns exist within consumer comments?
* When did the campaign receive the highest engagement?
* What strategies can help convert social media engagement into purchase behavior?

---

## 📂 Dataset

The research dataset consists of:

**19,461 Instagram comments**

The collected data included:

* Username
* Comment text
* Timestamp
* Engagement-related metadata

The comments were collected from KitKat India's official Instagram campaign posts using an Instagram Comments Export Chrome tool. The dataset covered the period from **2020 to early 2026**. 

> **Note:** Personally identifiable information from social-media users should not be uploaded to a public GitHub repository. Use an anonymized or aggregated dataset when publishing the project.

---

## 🛠️ Technologies & Tools

| Tool / Technology | Purpose                           |
| ----------------- | --------------------------------- |
| Python            | Data analysis and processing      |
| Pandas            | Data manipulation and aggregation |
| NumPy             | Numerical analysis                |
| TextBlob          | Sentiment analysis                |
| Matplotlib        | Data visualization                |
| Seaborn           | Visualization                     |
| Regex             | Text preprocessing                |
| Counter           | Keyword frequency analysis        |
| Chrome Extension  | Instagram comment extraction      |

The research methodology used Python, Pandas, NumPy, TextBlob, Matplotlib and Seaborn across multiple analytical stages. 

---

## 🔄 Project Workflow

```text
Instagram Campaign
        ↓
Comment Data Collection
        ↓
Data Cleaning & Preprocessing
        ↓
Exploratory Analysis
        ↓
Keyword Frequency Analysis
        ↓
Sentiment Analysis
        ↓
Purchase Intent Classification
        ↓
Customer Engagement Analysis
        ↓
Time-Series Analysis
        ↓
Business Insights
        ↓
Strategic Recommendations
```

---

# 📊 Analysis Performed

## 1️⃣ Brand Awareness Analysis

Keyword frequency analysis was used to identify the words most frequently appearing in consumer comments.

### Key Finding

**"KitKat" appeared 1,086 times**, making it the most frequently mentioned brand-related keyword.

Other frequently occurring terms included:

* "please" – 468
* "chocolate" – 463
* "love" – 430
* "need" – 301
* "where" – 232
* "want" – 225

These findings indicate strong brand salience and consumer awareness. 

---

## 2️⃣ Purchase Intent Analysis

A rule-based purchase-intent classifier was developed to categorize comments according to their expressed purchase motivation.

### Key Finding

| Purchase Intent  |     Share |
| ---------------- | --------: |
| Low Intent       | **92.5%** |
| High Intent      |  **4.9%** |
| Other Categories |  **2.8%** |

Approximately **18,001 comments** were classified as low purchase intent, while **959 comments** demonstrated high purchase intent. 

### Major Insight

The campaign generated substantial interaction, but most interactions did **not translate into strong purchase intent**.

This highlights an important:

> **Engagement → Conversion Gap**

---

## 3️⃣ Customer Engagement Analysis

The project developed a composite engagement score to evaluate the depth of individual interactions.

### Key Findings

* Average engagement score: **17.2 / 100**
* Peak engagement period: **13:00–16:00 UTC**
* Emoji usage: **51.1%**
* @mentions: **18.2%**
* Question marks: **7.2%**
* Hashtags: **3.3%**

The relatively low hashtag usage suggests an opportunity to improve campaign discoverability and user-generated content. 

---

## 4️⃣ Sentiment Analysis

TextBlob was used to classify comments into positive, neutral, and negative sentiment categories.

### Results

| Sentiment | Comments | Percentage |
| --------- | -------: | ---------: |
| Neutral   |   16,357 |  **84.1%** |
| Positive  |    2,594 |  **13.3%** |
| Negative  |      510 |   **2.6%** |

The overall average polarity score was **0.0524**, indicating a mildly positive overall sentiment. 

---

## 5️⃣ Campaign Performance Analysis

Weekly time-series analysis was performed using:

* Comment volume
* Net sentiment
* High purchase-intent rate

The analysis revealed that campaign engagement was **sporadic and burst-driven**, rather than consistently sustained throughout the study period.

A major spike occurred around mid-2024, reaching approximately **400 comments per day**. 

---

# 💡 Major Insights

### 🟢 Strong Brand Awareness

The high frequency of KitKat-related keywords demonstrates strong brand visibility within the campaign conversation.

### 🟢 Positive Brand Environment

Only **2.6% of comments were classified as negative**, while the majority were neutral or positive.

### 🟡 Strong Engagement but Limited Conversion

Although the campaign generated substantial participation, **92.5% of comments were classified as low purchase intent**.

### 🟡 Engagement Was Not Consistent

Campaign performance showed periodic spikes rather than sustained engagement.

### 🔴 Conversion Represents the Major Opportunity

The biggest strategic challenge identified by the study is converting social engagement into measurable purchase consideration.

These findings demonstrate the difference between **engagement breadth and conversion depth**. 

---

# 📈 Business Recommendations

Based on the analysis, the study proposes several strategies.

### 1. Conversion-Oriented Content

Introduce stronger calls-to-action such as:

* Product purchase links
* Limited-time offers
* Shoppable Instagram features
* Conversion-focused campaign posts

These should be prioritized during the identified **13:00–16:00 UTC engagement window**. 

### 2. Influencer Collaboration

Work with relevant micro- and mid-tier influencers whose audiences closely align with the campaign's target consumers.

### 3. Stronger Hashtag Strategy

The relatively low **3.3% hashtag usage** indicates an opportunity to increase:

* Discoverability
* User-generated content
* Organic reach
* Community participation

### 4. Social Listening

Implement continuous social listening to identify:

* Brand conversations
* Consumer concerns
* Reputation risks
* Emerging trends

### 5. Predictive Analytics

Future campaign analysis can incorporate:

* Machine learning-based purchase-intent classification
* AI-driven audience segmentation
* Predictive campaign performance models

These recommendations are based on the published study's findings. 

---

# 📁 Suggested GitHub Repository Structure

```text
kitkat-snap-to-decide-analysis/
│
├── README.md
│
├── data/
│   └── anonymized_comments.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_brand_awareness_analysis.ipynb
│   ├── 03_purchase_intent_analysis.ipynb
│   ├── 04_sentiment_analysis.ipynb
│   └── 05_campaign_performance.ipynb
│
├── src/
│   ├── data_cleaning.py
│   ├── sentiment_analysis.py
│   ├── purchase_intent.py
│   └── engagement_analysis.py
│
├── visualizations/
│   ├── brand_keywords.png
│   ├── purchase_intent.png
│   └── campaign_trajectory.png
│
├── paper/
│   └── published_research_paper.pdf
│
└── requirements.txt
```

---

# 📊 Example Visualizations

The project includes analytical visualizations covering:

* Top brand-related keywords
* Purchase-intent distribution
* Campaign performance trajectory
* Weekly comment volume
* Sentiment patterns
* Engagement behavior

---

# 🧠 Skills Demonstrated

This project demonstrates practical skills in:

**Data Analytics**

* Data Cleaning
* Exploratory Data Analysis
* Statistical Analysis
* Time-Series Analysis

**Python**

* Pandas
* NumPy
* TextBlob
* Regex
* Matplotlib
* Seaborn

**NLP**

* Text Preprocessing
* Keyword Extraction
* Sentiment Analysis
* Rule-Based Classification

**Marketing Analytics**

* Brand Awareness Analysis
* Customer Engagement
* Purchase Intent
* Campaign Performance
* Conversion Analysis

**Business Intelligence**

* Data-driven decision making
* Consumer behavior analysis
* Digital marketing strategy
* Campaign optimization

---

# 🏆 Research Publication

### Published Research Paper

**Title:**
*Analyzing Online Campaign Performance: A Study of KitKat's "Snap to Decide" Digital Campaign*

**Author:**
**S. Udhayanithi**

**Co-Author:**
**Dr. M. Iswarya**

**Institution:**
Hindusthan College of Engineering and Technology, Coimbatore

**Journal:**
International Journal of Advanced Research in Science, Communication and Technology (IJARSCT)

**Volume:** 6
**Issue:** 2
**Publication:** May 2026
**DOI:** 10.48175/IJARSCT-34801

The publication details are provided in the research paper. 

---

# 📚 Research Contribution

This project contributes a **multi-dimensional computational framework** for evaluating digital FMCG campaigns using real-world social media data.

The framework combines:

```text
Brand Awareness
       +
Purchase Intent
       +
Customer Engagement
       +
Sentiment
       +
Campaign Trajectory
       ↓
Digital Campaign Performance
```

The study demonstrates how social media comment data can be transformed into actionable marketing insights and highlights the importance of measuring **conversion-oriented outcomes alongside traditional engagement metrics**. 

---

# 🚀 Future Scope

Future development of this project can include:

* 🤖 Machine Learning-based purchase-intent prediction
* 🧠 Transformer-based sentiment analysis
* 📱 Multi-platform analysis across Instagram, YouTube and X
* 🎯 AI-based customer segmentation
* 📈 Predictive campaign performance modeling
* 🔎 Advanced social listening
* 🛒 Conversion prediction
* 📊 Interactive Power BI dashboards

---

# ⚠️ Data Privacy & Ethics

This project analyzes publicly available social-media interactions for academic research.

When reproducing or publishing this project:

* Do not publish usernames or personal identifiers.
* Use anonymized datasets.
* Respect platform terms of service.
* Avoid exposing private user information.
* Use aggregated results where possible.

---

# 👨‍💻 Author

## S. Udhayanithi

**MBA | Finance & Marketing | Data Analytics | Digital Marketing Analytics**

Interested in applying **data analytics, consumer insights, marketing analytics, and AI** to solve real-world business problems.

---

## ⭐ If You Find This Project Useful

If this project helps you understand **social media analytics, NLP, marketing analytics, or purchase-intent analysis**, consider giving the repository a ⭐.

---

### 📖 Publication

**DOI:** `10.48175/IJARSCT-34801`

**Research Area:** Digital Marketing Analytics | Social Media Analytics | Consumer Behavior | NLP | FMCG Marketing

---
