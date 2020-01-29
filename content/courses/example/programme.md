---
date: "2020-01-01T00:00:00Z"
draft: false
linktitle: Tips 3-4
menu:
  example:
    parent: Syllabus
    weight: 2
title: Syllabus
toc: true
type: docs
weight: 2
---

# Module programme

```{r, include=FALSE}
library(tidyverse)
library(kableExtra)
```

```{r, echo=FALSE}
text_tbl <- data.frame(
  Week = c("1", "2", "3", "4", "5", "6", "7", "8", "9", "10", "11", "12"),
  
  Date = c("30/01/2020", "06/02/2020", "13/02/2020", "20/02/2020", "27/02/2020", "05/03/2020", "12/03/2020", "19/03/2020", "26/03/2020", "23/04/2020", "30/04/2020", "07/05/2020"),
  
  Time = c("13:00-15:00", "13:00-15:00", "13:00-15:00", "13:00-15:00", "13:00-15:00", "13:00-15:00", "13:00-15:00", "13:00-15:00", "-", "13:00-15:00", "13:00-15:00", "13:00-15:00"),
  
  Topic = c("Intro & Spatial Data", "Point Data Analysis", "Flow Data Analysis", "Spatial Econometrics", "Assignment 1: Clinic", "Multilevel Modelling 1", "Multilevel Modelling 2", "Assignment 2: Clinic", "*No Lecture (Field class week)*", "Geographically Weighted Regression", "Spatio-Temporal Data Analysis", "Assignment 3: Clinic"),
  
  Staff = c("FR", "DAB", "DAB", "DAB", "DAB", "FR", "FR", "FR", "-", "FR", "FR", "FR") 
)

kable(text_tbl) %>%
  kable_styling("striped", full_width = F) %>%
  row_spec(9, bold = T, color = "white", background = "#a7a4a3")
``` 
Staff: FR: Francisco Rowe; DAB: Dani Arribas-Bel