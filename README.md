# 📊 Customer Segmentation & Web Analytics Analysis

## 📌 Overview
This project analyzes user behavior on a digital platform to identify distinct user segments based on engagement patterns and activity metrics. The objective is to understand how users interact with the platform and translate behavioral data into actionable business insights.

This project combines:
- 📊 Data analysis and segmentation modeling
- 🧠 Behavioral insight generation
- 🚀 An interactive deployed analytics application (Hugging Face Spaces)

---

## 🎯 Business Problem
Digital platforms often struggle to understand heterogeneous user behavior at scale.

This project addresses:
- How do user engagement patterns vary across users?
- Which user groups contribute most to platform activity?
- Where are opportunities to improve retention and activation?
- How can segmentation be operationalized for decision-making?

---

## 📂 Dataset
A sample dataset representing user behavioral activity was used for analysis due to size constraints.

- Contains user-level engagement metrics (frequency, activity patterns, interaction intensity)
- Full dataset excluded due to file size limitations
- Analysis performed on a representative sample sufficient to preserve behavioral patterns

---

## 🧠 Methodology

The analysis follows a structured end-to-end analytics workflow:

1. Data Cleaning & Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering (behavioral metrics)  
4. User Segmentation using clustering techniques (K-Means / RFM-inspired logic)  
5. Segment profiling and interpretation  
6. Insight generation and business recommendation mapping  

---

## 👥 User Segments Identified

### 🔵 Power Users
High-frequency, highly engaged users who consistently drive a large share of platform activity.

### 🟢 Regular Active Users
Moderately engaged users with stable but non-dominant usage patterns.

### 🟠 Low-Engagement / At-Risk Users
Users with infrequent activity and declining engagement trends, representing churn risk.

🔍 Key Insights
User engagement is highly concentrated within a small subset of “power users,” indicating strong usage skew.
A large proportion of users demonstrate low or inconsistent activity, representing retention risk.
Segmentation reveals clear behavioral clusters that are not visible in aggregate-level analysis.
Differentiated user groups enable more targeted engagement and retention strategies.
💡 Business Recommendations
Prioritize retention strategies for at-risk users through targeted re-engagement campaigns.
Improve onboarding flows to increase early-stage activation rates.
Introduce personalized experiences for mid-tier users to increase engagement frequency.
Implement loyalty mechanisms for high-value users to sustain long-term engagement.
🚀 Interactive Analytics Dashboard (Hugging Face Spaces)

To extend the analysis beyond static outputs, an interactive dashboard was developed and deployed using Hugging Face Spaces.

🔗 Live App

https://huggingface.co/spaces/akhand14/mgmt389_USDA_TEAM10

📌 Features
Interactive exploration of user segmentation results
Visualization of behavioral patterns across user groups
Dynamic filtering of engagement metrics
User-friendly interface for non-technical stakeholders
🎯 Purpose

This application transforms static analysis into an interactive decision-support tool, allowing stakeholders to explore segmentation insights without requiring technical expertise.

🧠 Value Add

Demonstrates end-to-end capability across:

Data analysis
Machine learning / segmentation
Deployment of an interactive analytics product
📌 Executive Takeaway

User behavior is highly unevenly distributed, with a small subset of users driving the majority of engagement. This segmentation framework enables targeted interventions to improve retention, activation, and overall platform efficiency.

🛠️ Tools Used

Python | Pandas | NumPy | Scikit-learn | Matplotlib | Seaborn | Hugging Face Spaces



