# Phase 3: Feature Engineering

Machine learning models require a structured, one-row-per-patient format. This phase transforms raw, longitudinal events into predictive features.

**Key Objectives:**
* Aggregate lab values across specific time windows.
* Derive encounter frequency and healthcare utilization indicators.
* Extract the most recent clinical events (latest labs, latest medications).
* Pivot longitudinal data from long to wide format.
* Prevent data leakage by dropping future variables prior to modeling.
