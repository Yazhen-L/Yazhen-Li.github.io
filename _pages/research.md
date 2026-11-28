---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 1
---

<style>
/* Font for the top navigation bar */
body .navbar,
body .navbar a,
body .navbar button,
body .navbar-brand,
body .navbar-nav,
body .nav-link,
body .navbar span:not(.fas):not(.far):not(.fab),
body .navbar *:not(i):not(svg):not(path):not(.fas):not(.far):not(.fab) {
  font-family: "Times New Roman", Times, serif !important;
}

/* Font for the search window */
body #search-modal,
body #search-modal *,
body .search-modal,
body .search-modal *,
body .search-overlay,
body .search-overlay * {
  font-family: "Times New Roman", Times, serif !important;
}
  
/* Times New Roman for the Research page */
body .post,
body .post *,
body .post-header,
body .post-header *,
body .post-title {
  font-family: "Times New Roman", Times, serif !important;
}

/* Make the Research page text slightly larger */
body .post {
  font-size: 18px !important;
}

body .post p,
body .post li {
  font-size: 18px !important;
}
</style>



## Temperature Measurement, Index Construction, and Electricity-Market Risk in ERCOT

**Role:** Researcher<br>
**Affiliation:** [RiskEcon<sup>®</sup> Lab at NYU](https://wp.nyu.edu/riskeconlab/)<br>
**Advisors:** [Dr. David K. A. Mordecai](https://riskeconomicsinc.com/david-k-a-mordecai/), [Dr. Gabriel Provencher Langlois](https://gabrielpl.com/), and [Dr. Christoph Graf](https://policyintegrity.org/about/bio/christoph-graf)<br>
**Status:** In progress

### Background

Non-catastrophic weather variation can create uncertainty in cash flows and other economic payoffs by changing the quantity of underlying production or consumption. Because such quantity exposure cannot be fully hedged using price-based instruments alone, weather derivatives condition payoffs on observable weather measurements and pre-specified indices such as Heating Degree Days (HDD) and Cooling Degree Days (CDD). Choices such as the underlying temperature observations, spatial aggregation method, and index construction can have temperature-index basis risk and electricity market implications.

The empirical scope of our research is the Texas Electric Reliability Council of Texas (ERCOT) market. The current work focuses on temperature measurement and regional temperature-index construction. Planned extensions examine relationships among regional temperature measures, ERCOT load, and nodal locational marginal prices, as well as extreme load and price observations and basis-risk and hedging analysis using realized electricity-market spread volatility.

### Research Questions

The following questions summarize the main aspects of this research that I have investigated to date:

- How sensitive are county-level temperature estimates to spatial sampling and interpolation methods?
- How do alternative population and manufacturing-employment weights change regional HDD and CDD baskets?
- After removing annual seasonality, how much short-run autocorrelation and volatility clustering remains in degree-day and temperature-anomaly series?
- After calendar-date seasonal adjustment, how closely do temperature-anomaly distributions and tails follow Gaussian benchmarks?

### My Work

My work has focused on four related components:
1. **Prototyping Errors and Sensitivity Analysis for Temperature Measurement Data Fusion**
2. **Regional Temperature Baskets and Their Potential to Explain Differences in Economic Exposure (e.g., Basis Risk)**
3. **Seasonality and Temporal Dependence**
4. **Gaussian Approximation and Tail Behavior of Regional Temperature Anomalies**

I independently implemented all code used in these analyses and prepared the accompanying research report documenting the data construction, methodology, empirical analyses, results, and current progress.<sup>1</sup>

<small><sup>1</sup> Source code and selected visualizations are available upon request.</small>

### Current Progress

Building on above analyses, I am currently working under the guidance of my advisors toward co-authoring research papers. 

### Future Work

Future work will:

- Extend the preceding research, co-advised by Dr. Mordecai and Dr. Provencher Langlois, to an analysis of nodal locational marginal price (LMP) responses. This extension will be primarily co-advised by Dr. Graf.

- Apply the nodal LMP response analysis within a joint peaks-over-threshold (POT) framework to estimate corresponding load and price extremes, while also examining occurrences of negative-price sign changes. This work will be primarily co-advised by Dr. Provencher Langlois.

- Conduct an empirical analysis, primarily co-advised by Dr. Mordecai, to estimate realized spread volatility and evaluate basis risk and hedging performance. This analysis will consider node-specific DAM–RT and TBx positions, as well as spreads across nodal baskets and seasonal strips, conditional on market-implied heat rates.

<hr class="research-divider">

## [Research Project Title]

Write a short explanation of the research question, the motivation, your role, methods, and main findings.

**Role:**  
**Advisor or Lab:**  
**Methods:**  
**Results:**  
**Status:** Completed or Ongoing
