# Chips-Customer-Behaviour-Analysis
R analysis of Woolworths chip trial — data prep, feature engineering, control store selection + significance testing

This project analyses a real-world supermarket product trial (Woolworths chips category) using R.
Objective:
Measure whether a trial store’s promotional activity led to a statistically significant lift in sales + customer transactions compared to a matched control store.

Tasks Completed

Task 1 — Data preparation + feature engineering
  loaded and cleaned the data
  filtered monthly totals
  created measures for total sales + total customers
  handled missing values + formatted date periods

Task 2 — Control store selection
  calculated the correlation between trial store & all stores
  calculated magnitude similarity (difference in totals)
  combined correlation & magnitude into a composite matching score
  selected Top 1 most similar store as control
    
Task 3 — Impact evaluation
  scaled pre-trial control sales to match trial baseline
  calculated percentage differences during the trial period
  computed standard deviation (pre-trial)
  t-test to determine statistical significance of results

Tools & Techniques
Category	Used
Language	R
Libraries	data.table, ggplot2
Methods	correlation scoring, magnitude scoring, t-test
Output charts	trend comparisons (sales & customers)

Key Result
The analysis statistically tests whether the trial store showed significant uplift beyond expected behaviour.



