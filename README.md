## yaml

title: “BIO2104 Formative Assessment 11: Mixed-Design Repeated Measures
ANOVA Using R” output: html\_document: keep\_md: true —

# BIO2104 Formative Assessment 11: Mixed-Design Repeated Measures ANOVA Using R

## Student Information

-   **Students:** Avila, Kristhea Andrey R. | Cataggatan, Cedrick A. |
    Chang, Jolin Sophia L. | Foja, Kurt Rommel R. | Idio, Aliyah Chloe
    M.
-   **Course:** BIO2104 - Biostatistics

## Assessment Title

-   Formative Assessment 11: Mixed-Design Repeated Measures ANOVA Using
    R

## Dataset Source

-   **Dataset:** `rats` Dataset from `nlmm` package
-   **Repository:** CRAN
-   **URL:** \[`rats` Dataset\]
    (<https://rdrr.io/cran/nlmm/man/rats.html>)

## Research Question

To determine whether rat body weight differs significantly across
treatment groups and measurement occasions. Specifically, investigate
whether the pattern of body weight changes over time differs depending
on the treatment received. 1. **Mixed-Design Repeated Measures ANOVA:**
Does the effect of treatment on rat body weight depend on the
measurement occasion?

## Software Used

-   **RStudio**

## Brief Description of the Analysis

This study performs a Mixed-Design Repeated Measures Analysis of
Variances (ANOVA) of rat growth with treatment `trt` and time `time` as
dependent variables. Twenty seven (27) surviving rats out of 30 were
recorded, each given separate treatments through their drinking water:
Control (no additives), Thyroxin, and Thiouracil. The body weights of
the rats were recorded at five measurement occasions: Baseline (Week 0),
Week 1, Week 2, Week 3, and Week 4.

## Required Packages / Libraries

To run this analysis successfully, ensure the following R libraries are
installed in your environment: \* `nlmm` \* `tidyverse` \* `rstatix` \*
`ggpubr`

## All dependencies can be installed in RStudio via:

`install.packages("nlmm", "tidyverse", "rstatix", "ggpubr")`
