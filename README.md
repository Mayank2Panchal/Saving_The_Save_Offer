# Saving_The_Save_Offer
# Saving the Save Offer: How Compliant Cancellation-Stage Retention Offers Shape Retention, Customer Inferences and Brand Outcomes in UK Subscription E-Commerce

**Author:** Mayank Panchal

**Supervisor:** Marco Gregori

**Institution:** Warwick Business School (WBS), The University of Warwick

**Program:** MSc Management

**Date:** August 2026

---

## 📋 Table of Contents

* [Project Overview](#-project-overview)
* [Research Background & Context](#-research-background--context)
* [Experimental Design & Methodology](#-experimental-design--methodology)
* [Key Findings & Empirical Results](#-key-findings--empirical-results)
* [Repository Structure](#-repository-structure)
* [Tech Stack & Analysis Pipeline](#-tech-stack--analysis-pipeline)
* [Managerial & Regulatory Implications](#-managerial--regulatory-implications)
* [Author & Academic Ethics](#-author--academic-ethics)

---

## 📖 Project Overview

Subscription e-commerce models frequently utilize last-minute retention incentives ("save offers") presented during the customer cancellation workflow. While widely practiced in industry, peer-reviewed experimental evidence examining the causal impact of randomized cancellation offers has been largely absent.

This dissertation investigates how legally compliant cancellation-stage retention interventions—specifically a **40% financial discount** versus a **flexibility offer** (pause or downgrade options) compared against a **no-offer control**—affect immediate customer retention, consumer inferences (exploitation and price fairness), perceived firm care, and downstream brand equity.

---

## 🏛️ Research Background & Context

* **Regulatory Urgency:** Situated within the UK **Digital Markets, Competition and Consumers (DMCC) Act 2024** (taking full effect before January 2027), which bans dark patterns and obstruction while legally permitting compliant counteroffers during online cancellation.


* **Research Questions:**
1. *RQ1:* Does the type of compliant cancellation-stage retention offer affect immediate retention and post-exit brand outcomes, and through which customer inferences do any effects operate?


2. *RQ2:* Does perceived customer value condition these effects, and can a managerially usable threshold be identified?





---

## ⚙️ Experimental Design & Methodology

* **Design:** Between-subjects randomized experimental design with a single factor at three levels (Control vs. Discount vs. Flexibility) administered via Qualtrics.


* **Sample:** $N = 97$ validated UK respondents (post-screening from 127 raw responses: consented $n=124$, UK residents $n=114$, active subscribers in past 24 months $n=108$, reached manipulation $n=97$).


* **Experimental Arms:**
* **Control ($n = 30$):** Standard neutral cancellation confirmation.


* **Discount ($n = 38$):** 40% off the next 3 boxes.


* **Flexibility ($n = 29$):** Pause deliveries for up to 2 months or switch to a cheaper plan (Standard/Mini).




* **Measures:** Multi-item validated Likert scales ($\alpha = 0.75$ to $0.88$) for **Exploitation Inference**, **Price Fairness**, **Perceived Care**, **Brand Trust**, **Resubscription Intention**, **Net Promoter Score (NPS)**, and **Perceived Customer Value** (moderator).



---

## 🔍 Key Findings & Empirical Results

1. **Behavioral Retention ($H_1$ Supported):**
* Control group retention: **0.0%** ($0/27$).


* Discount offer retention: **37.0%** ($13/35$, $g = +0.99$, $p < 0.001$).


* Flexibility offer retention: **17.0%** ($5/29$, $g = +0.61$, $p = 0.023$).




2. **Perceptual Costs & Inferences ($H_2$ & $H_4$ Supported, $H_3$ Rejected):**
* **Exploitation Inference:** Offers significantly increased perceptions of being overcharged and pressured ($F = 21.13, p < 0.001, \eta^2 = 0.310$).


* **Perceived Care:** Both offers sharply reduced perceived firm care ($F = 18.55, p < 0.001, \eta^2 = 0.283$).


* **Price Fairness:** Abstract fairness declined across offer arms ($F = 6.31, p = 0.003, \eta^2 = 0.118$), revealing that exit episodes impact baseline fairness evaluations.




3. **Robustness & Correction:**
* **Benjamini-Hochberg FDR Correction:** **7 of 9 outcomes** survived false discovery rate correction at $q = 0.05$.


* **Data Quality Robustness:** Results remained exceptionally robust across data quality screening subsets ($n=85$ and $n=74$).




4. **Exploratory Mediation & Moderation:**
* **Mediation:** Price fairness significantly mediated the negative indirect path from offers to brand trust (Discount indirect: $-0.30$, Flexibility indirect: $-0.39$).


* **Moderation (Johnson-Neyman Floodlight Analysis):** Identified a critical **4.64 threshold** on the 7-point perceived customer value scale ($70\%$ of the sample). Above this threshold, the relationship-safe flexibility offer **significantly erodes brand trust** among high-value customers ($b = -0.657, p = 0.002$).





---

## 📁 Repository Structure

```text
├── Dissertation.pdf                     # Full 62-page MSc Dissertation manuscript[cite: 5]
├── Proposal.pdf                         # Initial research proposal document[cite: 91]
├── Full survey.pdf                      # Complete Qualtrics instrument & stimuli screenshots[cite: 67]
├── Logbook.txt                          # Complete Python analysis log, outputs & statistical tests[cite: 4]
├── Qualtricsdata.xlsx                   # Raw survey export data from Qualtrics[cite: 97]
├── Participant consent form.pdf         # Ethics participant consent form[cite: 97]
├── Participant information leaflet.pdf  # Ethics participant information leaflet[cite: 98]
└── README.md                            # Project documentation

```

---

## 🛠️ Tech Stack & Analysis Pipeline

* **Programming Language:** Python 3


* **Core Libraries:** `pandas`, `SciPy`, `statsmodels`, `matplotlib`, `seaborn`


* **Statistical Methods:**
* Principal Component Analysis (PCA) & Cronbach's Alpha ($\alpha$) reliability testing


* One-way ANOVA, Welch pairwise contrasts, Kruskal-Wallis tests, and Hedges' $g$ effect sizes


* Benjamini-Hochberg False Discovery Rate (FDR) correction


* Bootstrapped Mediation Analysis (3,000 resamples)


* Moderated Regression & Johnson-Neyman Floodlight Analysis





---

## 🎯 Managerial & Regulatory Implications

1. **The Compliance Trade-off:** Zero-retention control proves that retention offers drive the behavioural rescue effect, but they carry unavoidable inferential costs (exploitation and reduced care).


2. **Strategic Offer Choice:** Discounts maximize short-term retention at the expense of exploitation spikes; flexibility offers protect recommendations but degrade trust among high-value segments.


3. **Targeting High-Value Customers:** Retention managers must avoid deploying generic flexibility/pause offers to high-value subscribers (>4.6 perceived value threshold), as it triggers customer betrayal dynamics.



---

## 👥 Author & Academic Ethics

* **Author:** Mayank Panchal (Student ID: `5746060`)


* **Academic Supervisor:** Dr. Marco Gregori


* **Ethical Approval:** Granted low-risk ethics approval by Warwick Business School (WBS) Research Ethics Committee under University of Warwick guidelines.
