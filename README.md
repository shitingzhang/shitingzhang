# Hi, I’m Shiting Zhang 👋

My background is in rehabilitation. I’m interested in how health data can help us understand the care patients receive and what happens after they leave.

## A decision I changed

**What does a measure of therapy time actually capture?**

CMS records therapy minutes during the first two weeks of a rehabilitation stay. My first analysis divided those minutes by Medicare-covered days across the entire stay. Two facilities could record the same therapy time and get different ratios simply because their patients stayed for different lengths of time.

I changed the question. **How was therapy time divided among different types of sessions during the first two weeks?**

[Read the study design](https://github.com/shitingzhang/rehab-analytics/blob/main/docs/study_design.md)

## Rehab Analytics

I linked four public CMS files. The main analysis covered **938 U.S. inpatient rehabilitation facilities**. After adjusting for facility and patient mix, a higher share of group or concurrent therapy time was associated with both higher community discharge and higher readmission rates.

[![Forest plot of adjusted facility-level associations between therapy mix, community discharge, readmission and Medicare payment](https://raw.githubusercontent.com/shitingzhang/rehab-analytics/main/reports/figures/model_a_forest.png)](https://github.com/shitingzhang/rehab-analytics#results)

[Explore the project](https://github.com/shitingzhang/rehab-analytics) · [See the results](https://github.com/shitingzhang/rehab-analytics#results) · [Reproduce the analysis](https://github.com/shitingzhang/rehab-analytics#reproduce-the-analysis)

## What I’d like to study next

If we could link length of stay, discharge destination, and readmission for each patient, could we tell whether earlier discharge helps explain the pattern?
