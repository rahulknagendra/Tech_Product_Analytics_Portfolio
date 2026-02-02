# Tech Product Analytics Portfolio

Rahul Nagendra | [rahulknagendra@gmail.com](mailto:rahulknagendra@gmail.com) | [LinkedIn](https://www.linkedin.com/in/rahul-k-nagendra) | [GitHub](https://github.com/rahulknagendra)

## About Me

Recent UCLA graduate with a computational sociology background as well as D1 tennis data analytics consulting experience. Currently work in business strategy, product analytics, and product management at FairQuanta, a deep tech human-centered design startup. The behavioral analysis framing throughout this portfolio reflects that training: understanding behavior as emerging from social context and position, not isolated individual traits.

## Overview

Three projects spanning the tech product analytics lifecycle: activation, engagement, and retention. Each project demonstrates behavioral analysis: understanding not just *what* users do, but *how* and *why* behavior unfolds the way it does.

## Projects

### [Firebase Activation Analytics](https://github.com/rahulknagendra/Firebase_Activation_Analytics)
**Domain:** Mobile Gaming · Product Analytics

**Question:** What predicts whether new users reach the activation milestone?

**Topic** Tracked 4,319 new installs through an activation funnel using conversion metrics and cohort segmentation in BigQuery to identify what distinguishes users who activate from those who don't (5.7M events).

**Finding** First-game winners who continue playing activate at 42% vs 20% for first-game losers who continue. The same action (continuing to play) converts at 2x the rate depending on context. 67% of activation happens within the first hour—the first session is the critical window.

**Tech Stack:** BigQuery, Python (pandas, numpy, matplotlib), Looker Studio

**Methods:** Funnel analysis, stage-by-stage conversion rates, time-to-event analysis, cohort segmentation, behavioral segmentation

**Behavioral Analysis:** The same action (continuing to play) represents momentum after a win but persistence after a loss. Conditioning on outcome reveals that momentum converts at over twice the rate of persistence. The behavior is identical; the context changes its meaning.

---

### [GitHub Engagement Analytics](https://github.com/rahulknagendra/Github_Engagement_Analytics)
**Domain:** Developer Platforms · Engagement Metrics

**Question:** What predicts how activated users engage?

**Topic** Measured engagement through consistency and frequency using DAU/WAU/MAU and stickiness ratios with cohort retention analysis, plus A/B test methodology with power analysis and balance checks on API-collected data (282K commits).

**Finding** Users who follow more than they're followed ("Consumers") are 1.93x more likely to show high engagement than users with more followers ("Producers"). Social consumption correlates with engagement more than social visibility does. The analysis separates engagement into consistency (showing up) and frequency (intensity when present).

**Tech Stack:** GitHub REST API, BigQuery, Python (pandas, numpy, matplotlib, scipy), Looker Studio

**Methods:** API data collection, cohort retention, DAU/WAU/MAU, stickiness ratios, A/B test methodology (experiment design, power analysis, balance checks, t-tests, confidence intervals, effect size)

**Behavioral Analysis:** Users are categorized not by follower count alone, but by the relationship between followers and following: Producers (followers exceed following) versus Consumers (following exceeds followers). The counter-intuitive finding that Consumers are 1.93x more likely to show high engagement than Producers suggests social consumption correlates with higher engagement more than social visibility.

---

### [KKBox Retention Analytics](https://github.com/rahulknagendra/KKBox-Retention-Analytics)
**Domain:** Music Streaming · Subscription Retention
**Question:** What predicts subscription churn?

**Topic** TBA

**Finding** TBA

**Tech Stack:** BigQuery (392M records), Python (pandas, numpy, matplotlib, statsmodels, sklearn), Looker Studio

**Methods:** Retention curves, cohort analysis, churn segmentation, behavioral segmentation, feature engineering, predictive modeling (logistic regression, AUC, precision/recall, feature importance)

**Behavioral Analysis:** TBA

---

## Analytical Approach

**Behavioral analysis throughout.** Each project goes beyond standard metrics to examine *how* behavior unfolds: activation sequences, engagement patterns, disengagement pathways. This framing, informed by my sociology background, asks why users behave differently, not just whether they do.

**Statistical and research rigor.** Effect sizes with confidence intervals, not just p-values. Power analyses to contextualize findings. Sensitivity tests across threshold choices. Explicit acknowledgment of limitations and selection effects. This reflects training in research methodology.

**Business-connected insights.** Every analysis connects to actionable recommendations: which users to target, which features to promote, which interventions to test. Technical work serves product decisions.

## Technical Skills

- **SQL:** Complex queries, CTEs, window functions, BigQuery (300M+ row tables)
- **Product Metrics:** Funnel conversion, DAU/WAU/MAU, retention curves, cohort analysis, churn segmentation
- **A/B Testing:** Experiment design, power analysis, balance checks, statistical significance
- **Python:** pandas, numpy, matplotlib, statsmodels for analysis and visualization
- **Research Methods:** Effect sizes with confidence intervals, sensitivity testing, limitation acknowledgment
- **Dashboards:** Looker Studio interactive dashboards with cross-filtering

---

*Each project folder contains notebooks, documentation, and data dictionaries. See individual README files for setup instructions and methodology details.*
