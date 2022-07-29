# Bidirectional associations between social isolation and ADHD across ages 5, 7, 10, and 12
[Katherine N Thompson](https://twitter.com/KTNThompson)

April, 2022

***

This repository holds code for for manuscript titled "Bidirectional associations between childhood social isolation and ADHD". Analyses include random intercept cross-lagged panel models (RI‐CLPM) of social isolation and ADHD symptoms at ages 5, 7, 10 and 12. Sex, SES, and informant differences were exminaed using multiple group RI-CLPM. Longitudinal mediation analyses were conducted to see if prosocial or antisocial behaviours mediated the association between ADHD and social isolation. All data from the E-Risk Study. 

For greater clarity when reviewing the code and results for this manuscript, this repository has been converted into an R pages website. **The website can be accessed here: ** 

Analyses for this project were conducted in R (Version 4.0.3). Below names and locations for all  scripts are listed, with a brief explanation of what each script entails, for more detail please go to the [website](). 


***

**RI-CLPM** 

1. RICLPMcomb_isolation_adhd.Rmd. CLPM and RI-CLPM for combined parent and teacher report data. Constraint testing for CLPM and RI-CLPM, separated by inattention, hyperactivity, and total ADHD models. 
                
***


**Sex, SES, and informant differences** 

1. RICLPM_isolation_adhd.Rmd. All CLPM and RI-CLPM run separately for mother and teacher report. Constraint testing for CLPM and RI-CLPM, separated by inattention, hyperactivity, and total ADHD models. 
2. RICLPM_isolation_adhd_sex.Rmd. Multiple group RI-CLPM computed to assess sex differences. Combined report, mother report, and teacher report computed for hyperactivity, inattention, and total ADHD symptoms. Constraint testing applied throughout. 
3. RICLPM_isolation_adhd_SES.Rmd. Multiple group RI-CLPM computed to assess SES differences. Combined report, mother report, and teacher report computed for hyperactivity, inattention, and total ADHD symptoms. Constraint testing applied throughout. 
                
***

**Longitudinal mediation** 

1. mediation_model_isolation_adhd.Rmd. Longitudinal mediation using 3 variable RI-CLPM to assess mediator effects of prosocial behaviour and antisocial behaviour. Combined mother and teacher report only. Longitudinal mediation computed for hyperactivity, inattention, and total ADHD symptoms. Constraint testing applied throughout. 

***

**Sensitivity analyses** 

1. RICLPM_measurement_model_isolation_adhd.Rmd. Using multiple group RI-CLPM to assess measurement invariance in 4 steps. Step 1: the configural model, Step 2: weak factorial invariance, Step 3: strong factorial invariance, Step 4: the latent measurement model RI-CLPM. 

***
