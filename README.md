## I do my thing and you do your thing: Recognising the importance of inter-individual variation in the roosting behaviours of free-ranging bats

This repository contains both the data and code used to document individual differences in roost usage of bats at a maternity colony. All analysis was done using R version 4.3 (R Core Team (2020)).

**ABSTRACT**

Individuals within the same population can differ considerably. Inter-individual behavioral variation can be substantial and within individual-variation is often limited relative to the whole population. This variation is important to consider because population (i.e., evolutionary) responses to environmental conditions are determined by the combination of individual responses, not by the average response of the population. Individual variation is often not considered when discussing population dynamics, because characterizing inter-individual variation requires repeated observations of the same individual, which is difficult to achieve in natural settings. We used a system of eleven monitored roost boxes to document the roost selection patterns of free-ranging little brown myotis (Myotis lucifugus) from 2012-2019 to quantify their inter-individual variation in the roosting behaviors. By comparing mixed-effects models with and without an individual random effect, we determined that variation in roost use can be at least partially attributable to inter-individual differences, with individuals responding to environmental conditions within a consistent narrow spectrum of the total population variance. Our results suggest that bat roosting behaviors are explained, at least in part, by underlying personality traits, similar to what has been identified in captive experiments, however this connection should be more directly tested in future studies.

---

Guide to the files:

aic_code.Rmd
- code for generating AIC values for comparing estimating models
  
figure_code.Rmd
- code for creating figures and tables

data_wrannglign.Rmd
- code for wrangling and filtering all recorded data into the used sample

both_use_reads.Rdata
- file containing observations included in analysis 
