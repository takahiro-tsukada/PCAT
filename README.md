# Preference and Consistency Assessment Tool (PCAT)
![DOI](https://zenodo.org/badge/1374554834.svg)](https://doi.org/10.5281/zenodo.22815301)
## Overview
PCAT is a browser-based experimental framework designed for psychiatric, clinical psychological, and behavioral research. It quantifies subjects' preference stability, choice consistency, and cognitive friction when evaluating visual or physical stimuli (e.g., snacks, facial expressions, or option choices).

PCAT enables researchers to examine preference structures and cognitive biases across various paradigms—including clinical populations (e.g., addictions, compulsive traits) and healthy controls—while offering mechanisms to detect careless or unfaithful responding during decision-making tasks.

## Key Innovations & Experimental Features

1. **Artificial Inconsistency Induction via Duplicate Pair Presentations**
   - Traditional paired-comparison methods often yield low variance in Kendall's consistency index ($\zeta$). 
   - PCAT intentionally introduces duplicate stimulus pairs at random intervals to trigger cognitive conflicts and force potential inconsistencies. This design expands the dispersion of $\zeta$, enabling precise detection of cognitive fluctuation, choice instability, or unfaithful responding.

2. **Multidimensional Cognitive & Behavioral Metrics**
   - **Consistency Index ($\zeta$):** Measures circular triadic inconsistencies across forced-choice pairs.
   - **Test-Retest Reliability ($\tau$):** Calculates Kendall's rank correlation across multiple experimental sessions.
   - **Micro-Level Response Latency Tracking:** Captures reaction time for each choice, allowing researchers to examine effort allocation, decision fatigue, and careless clicking.
   - **Group Comparisons:** Built-in categorization for independent variables (e.g., Control vs. Patient groups) to analyze interactions between clinical status, response time, and choice consistency.

3. **Client-Side Data Persistence**
   - Utilizes `localStorage` for cross-day multi-session testing without requiring dedicated backend infrastructure. Exports comprehensive subject data directly to CSV.

## Author & Citation
- **Author:** Takahiro Tsukada
- **Repository / DOI:** Registered via Zenodo.
