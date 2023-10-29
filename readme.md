# RVR NSSP Differ

Personal project to keep track of the weekly releases of the [RVR NSSP ED](https://data.cdc.gov/Public-Health-Surveillance/2023-Respiratory-Virus-Response-NSSP-Emergency-Dep/vutn-jzwm) numbers and smoosh everything into a single, usable dataframe and file.

I like to keep track of how data changes over time, and think I can just do this myself.

## Data I/O

### In

I think I want to pull this down every week and stick it in `data\raw`

- Pulling from [2023 Respiratory Virus Response - NSSP Emergency Department Visits - COVID-19, Flu, RSV, Combined](https://data.cdc.gov/Public-Health-Surveillance/2023-Respiratory-Virus-Response-NSSP-Emergency-Dep/vutn-jzwm)
- Maybe in the future, should pull from [2023 Respiratory Virus Response - NSSP Emergency Department Visits - COVID-19, Flu, RSV, Combined – by Demographic Category](https://data.cdc.gov/Public-Health-Surveillance/2023-Respiratory-Virus-Response-NSSP-Emergency-Dep/7xva-uux8)

### Out

I think I want to make a rolling, combined dataframe in `data\out` in csv so we can diff what changes from week to week.
