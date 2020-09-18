# STA360project: Stop and Frisk Data
## Authors: Cindy Wang, Evelyn Yun, Lynn Fan

## (i) Background Information
STA360 Final Project Report
Racial profiling in policing has always been a huge point of contention. It is defined as police practice that relies on certain racial characteristics they believe to be associated with crime. This issue is especially prominent in selective policing strategies such as “stop-and-frisk”, i.e. deciding which pedestrains to search, question, or frisk, a program in New York City that has caused numerous civil rights controversies. Police have defended the strategy by claiming that, while stop-rates are higher for non-white citizens, it only reflects reasonable prior knowledge or experience such as historic crime rates by race, or that other counfounding factors such as variation between precincts (neighbourhoods).

## (ii) Goals, relevant issues, and challenges
Our goal is to find out whether minorities (black and hispanic citizens) are disproportionately targeted even when taking into account to historic crime rates (approximated by arrest rates from the previous year) and variances in precinct as a random effect. To do this, we take the approach of modelling stop rates based on previous year’s arrests, categorized by ethnicity and crime type, while making precinct a random effect in the sampling model. We then examine the coefficients of the posterior distribution to see whether past year’s crimes would affect minority and white group stop rates in a similar way.
