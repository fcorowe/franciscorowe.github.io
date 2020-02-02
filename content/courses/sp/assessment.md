---
date: "2020-01-29T00:00:00+01:00"
draft: false
linktitle: Assessment
menu:
  sp:
    parent: Spatial Analysis
    weight: 3
title: Assessment
toc: true
type: docs
weight: 3
---

The final module mark is composed of the **three** assignments. Together they are designed to cover the materials introduced in the entirety of content covered during the semester.

* Assignment 1 (33%)
* Assignment 2 (33%)
* Assignment 3 (34%)

Assignments will be prepared in the R Notebook format and then converted into
a self-contained HTML file that will then be submitted on Turnitin.

Submission is electronic only via Turnitin on VITAL.

Maximum word count: 1,500 words, excluding figures and references. As per School Assessment Guidelines, *over-length submission will be capped at 40%*. The assignment deadline is specified below. Assignments submitted after this deadline will be penalised 5% per working day late. Assignments submitted more than five working days late will be awarded a mark of zero. *Mitigating Circumstances* for late submission must be submitted for consideration via the Student Support Office (Ground Floor, Roxby Building; email: soessouth@liverpool.ac.uk).

**Marking criteria**: Standard Environmental Sciences School marking criteria apply, with a stronger emphasis on evidencing the use of regression models, critical analysis of results and presentation standards.

# Assignment 1

Assigment 1 assesses teaching content from Weeks 1 to 4. 

**Deadline**: 14:00pm, March 3rd, 2020.

Using a new batch of house prices from the Land Registry (see data provided), carry out the
following analysis in an analogous way to how they were performed in class:

* KDE of house transactions.

* Create a surface map of the house prices in the dataset. To do that, use spatial
interpolation and, in particular, an inverse distance weight approach.

* Fit several regression models to explain the (log of) house prices as a function of whether
they are newly built houses and the IMD score of the area where they are located. Include
at least:
1. Baseline non-spatial regression.
2. Spatial FE estimation based on two-digit postcodes.
3. Baseline regression with an additional spatial lag of the IMD Score (Note you will have to
select a spatial weights matrix and justify it.)

* Discuss the model estimation results, particularly:

    - Think about the advantages and limitations of modelling house prices with a spatial FE model,
especially from the perspective of the structure of housing price data.
    - If the higher-level units were LSOAs (rather than the two-digits postcode geographical
units) and LSOA dummy variables were used in the spatial fixed effect model, could you still
obtain the regression coefficients of the IMD score variable? Hint: IMD scores are also
measured at the LSOA level.

*Data*

Data to complete the assignment will be available on VITAL. The shapefile contains house
price information for Liverpool in 2014 (same data used in practice).

# Assignment 2 

Assigment 2 assesses teaching content from Weeks 6 and 7.

**Deadline**: 14:00pm, March 31st, 2020.

Following the examples in class:

* Fit various regression models to your dependent variable of choice as a function of at least three independent variables at your level 1 scale and at least one at you level 2 scale or higher orders. Include at least:
1. A OLS regression model;
2. A null multilevel (baseline) regression model;
3. A random intercept model;
4. A random slope model or a random intercept + slope model;

* Provide a short justification of the independent variables included in your models;

* Justify the inclusion of the chosen variable in your level-2 or higher scales;

* Create caterpillar plots and/or maps to visualise the extent of variation in the estimated random effects in your models;

* Analyse and discuss:
1. the extent of variation in the dependent variables at two or more geographical scales (variation at which geographical scale explains most of variance in your dependent variable);
2. the random intercept estimate(s) from your model(s) (what can they tell you about the difference between groups / areas? are they statistically significantly different?);
3. the random slope estimate(s) from your model(s) (to what extent does the relationship between your dependent and independent variables vary across groups / areas? are they statistically significantly different?).

Ensure you appropriately describe the structure of the data and identify the various geographical scales of analysis (i.e. level-1, level-2 or higher-level units)

*Data*

Data to complete the assignment are available on VITAL. Alternatively you can source your own data.

# Assignment 3

Assigment 3 assesses teaching content from Weeks 10 and 11. 

**Deadline**: 14:00pm, May 8th, 2020.

Following the examples in class:
* Fit various regression models to your dependent variable of choice as a function of at least three independent variables. Include at least:

1. A OLS regression model;
2. A Geographically Weighted Regression (GWR) model;
3. A spatio-temporal (SP) regression model;
4. A visual SP representation of your variables;

* Analyse and discuss:
1. How the OLS, GWR and SP results differ (How do regression coefficients vary across space? Is this variation statistically significant?)
2. How do coefficients change over time? Why? 
2. Are GWR and/or SP models needed? Why? 
3. What is the appropriate bandwidth for your GWR? Why?

*Data*

Data to complete the assignment are available on VITAL. Alternatively you can source your own data.
