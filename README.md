# Tech Product Analytics Portfolio

Rahul Nagendra | [rahulknagendra@gmail.com](mailto:rahulknagendra@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rahul-k-nagendra) | [GitHub](https://github.com/rahulknagendra) | [Resume](https://docs.google.com/document/d/1YlK8RBchv9kNl6wKHJyussihSykrQk_NUuCARAT2cOM/edit?usp=drive_link)

## About Me

Recent UCLA graduate with a computational sociology background as well as D1 tennis data analytics consulting experience. Currently work in business strategy, product analytics, and product management at FairQuanta, a deep tech human-centered design startup. The behavioral analysis framing throughout this portfolio reflects that training: understanding behavior as emerging from social context and position, not isolated individual traits.

## Overview

Three projects spanning the product analytics lifecycle (activation, engagement, retention) and a network analysis project examining virality in social platforms. Each demonstrates behavioral analysis informed by my computational sociology background: understanding not just *what* users do, but *how* and *why* behavior unfolds.

## Projects

### [Firebase Activation Analytics](https://github.com/rahulknagendra/Firebase_Activation_Analytics)
**Domain:** Mobile Gaming · Product Analytics

**Question:** What predicts whether new users reach the activation milestone?

**Topic:** Tracked 4,319 new installs through an activation funnel using conversion metrics and cohort segmentation in BigQuery to identify what distinguishes users who activate from those who don't (5.7M events).

**Finding:** First-game winners who continue playing activate at 42% vs 20% for first-game losers who continue. The same action (continuing to play) converts at 2x the rate depending on context. 67% of activation happens within the first hour—the first session is the critical window.

**Tech Stack:** BigQuery, Python (pandas, numpy, matplotlib), Looker Studio

**Methods:** Funnel analysis, stage-by-stage conversion rates, time-to-event analysis, cohort segmentation, behavioral segmentation

**Behavioral Analysis:** The same action (continuing to play) represents momentum after a win but persistence after a loss. Conditioning on outcome reveals that momentum converts at over twice the rate of persistence. The behavior is identical; the context changes its meaning.

---

### [GitHub Engagement Analytics](https://github.com/rahulknagendra/Github_Engagement_Analytics)
**Domain:** Developer Platforms · Engagement Metrics

**Question:** What predicts how activated users engage?

**Topic:** Measured engagement through consistency and frequency using DAU/WAU/MAU and stickiness ratios with cohort retention analysis, plus A/B test methodology with power analysis and balance checks on API-collected data (282K commits).

**Finding:** Users who follow more than they're followed ("Consumers") are 1.93x more likely to show high engagement than users with more followers ("Producers"). Social consumption correlates with engagement more than social visibility does. The analysis separates engagement into consistency (showing up) and frequency (intensity when present).

**Tech Stack:** GitHub REST API, BigQuery, Python (pandas, numpy, matplotlib, scipy), Looker Studio

**Methods:** API data collection, cohort retention, DAU/WAU/MAU, stickiness ratios, A/B test methodology (experiment design, power analysis, balance checks, t-tests, confidence intervals, effect size)

**Behavioral Analysis:** Users are categorized not by follower count alone, but by the relationship between followers and following: Producers (followers exceed following) versus Consumers (following exceeds followers). The counter-intuitive finding that Consumers are 1.93x more likely to show high engagement than Producers suggests social consumption correlates with higher engagement more than social visibility.

---

### [KKBox Retention Analytics](https://github.com/rahulknagendra/KKBox-Retention-Analytics)
**Domain:** Music Streaming · Subscription Retention

**Question:** What predicts subscription churn?

**Topic:** Analyzed subscription retention across 970K users through cohort retention curves and churn segmentation, then built a predictive model to identify at-risk subscribers and characterized three distinct disengagement pathways in listening behavior (392M records).

**Finding:** Auto-renewal users churn at 3.8% vs 30.5% for manual renewal, an 8x difference. The predictive model (AUC=0.925) reveals three disengagement pathways: volume-led (listening hours drop first), completion-led (song finish rate drops first), and exploration-led (new music discovery drops first). Same outcome, different behavioral signatures.

**Tech Stack:** BigQuery (392M records), Python (pandas, numpy, matplotlib, statsmodels, sklearn), Looker Studio

**Methods:** Retention curves, cohort analysis, churn segmentation, behavioral segmentation, feature engineering, predictive modeling (logistic regression, AUC, precision/recall, feature importance)

**Behavioral Analysis:** Disengagement is not monolithic. A user whose listening hours drop while song completion stays high differs from one whose completion drops while hours stay constant. The first pattern suggests reduced time; the second suggests waning interest. Same churn risk, different underlying causes, different intervention implications.

---

### [Reddit Network Analytics](https://github.com/rahulknagendra/Reddit_Network_Analytics)
**Domain:** Social Media · Network Virality

**Question:** What predicts how viral content spreads?

**Topic:** Analyzed whether viral discussion growth is driven by who participates or what they say by modeling Reddit conversations as networks (302K comments, 9 subreddits) in the 4 months after ChatGPT’s launch. Measured users’ structural positions (e.g., community bridges), classified comment emotion at scale, and compared which better predicts discussion cascade size.

**Finding:** Users bridging multiple communities seed discussions that grow 50% larger on average, while comment emotion shows no relationship with cascade size. Network position predicts spread; emotional content does not. These bridge users also communicate with more emotional moderation across all dimensions.

**Tech Stack:** BigQuery (recursive CTEs), Python (pandas, numpy, matplotlib, networkx, networkit, transformers), Looker Studio

**Methods:** Network analysis (graph construction, centrality measures, betweenness), community detection (Louvain), emotion classification (ModernBERT, GoEmotions, PCA), cascade extraction, bridge user identification

**Behavioral Analysis:** Network position predicts cascade outcomes while emotional content does not, challenging content-focused virality frameworks. Spread depends less on emotional resonance and more on the structural position of the author. The emotional moderation of bridge users suggests these positions may select for or encourage measured communication styles.

---

## Analytical Approach

**Behavioral analysis throughout.** Each project goes beyond standard metrics to examine *how* behavior unfolds: activation sequences, engagement patterns, disengagement pathways. This framing, informed by my sociology background, asks why users behave differently, not just whether they do.

**Statistical and research rigor.** Effect sizes with confidence intervals, not just p-values. Power analyses to contextualize findings. Sensitivity tests across threshold choices. Explicit acknowledgment of limitations and selection effects. This reflects training in research methodology.

**Business-connected insights.** Every analysis connects to actionable recommendations: which users to target, which features to promote, which interventions to test. Technical work serves product decisions.

## Technical Skills

- **SQL:** Complex queries, CTEs, window functions, recursive queries, BigQuery (300M+ row tables)
- **Product Metrics:** Funnel conversion, DAU/WAU/MAU, retention curves, cohort analysis, churn segmentation
- **A/B Testing:** Experiment design, power analysis, balance checks, statistical significance
- **Python:** pandas, numpy, matplotlib, statsmodels for analysis and visualization
- **Research Methods:** Effect sizes with confidence intervals, sensitivity testing, limitation acknowledgment
- **Dashboards:** Looker Studio interactive dashboards with cross-filtering

---

*Each project folder contains notebooks, documentation, and data dictionaries. See individual README files for setup instructions and methodology details.*
