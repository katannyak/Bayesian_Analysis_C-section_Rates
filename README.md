# A Bayesian Analysis of Cesarean sections rates caused by labor induction

### I. SUMMARY
In this project, I re-evaluate the results of the ARRIVE trial (Grobman, 2018) using a Bayesian approach. This study, published in the New England Journal of Medicine, examined, among many other outcomes, whether elective induction of labor compared to no induction in first-time mothers effected the occurance of cesarean section (C-section). The data was analyzed using classical statistical methods. Here, I examine the data using Bayesian inference and compare my results to those of the study. This study was of particular interest as I am 40 weeks pregnant (at the time of writing this report) and so I have a strong personal interest in the findings of this study and how the data was interpreted. C-section is a major surgery, often an unplanned emergency surgery, that is associated with increased rate of infection, a longer hospital stay and recovery time for mother, and unfavorable outcomes for baby. Therefore, it is important to develop evidence-based delivery room practices and protocols that minimize the need for C-sections. 

### II. BACKGROUND AND SIGNIFICANCE: ARRIVE TRIAL
The recommendations for the timing of labor delivery seek to balance and maximize the postive outcomes for mother and baby. For mothers that do not have any medical complications, i.e. medical indication, the time of delivery is a bit of Golilocks scenerio: delivery before 39 weeks 0 days or at or beyond 41 weeks of gestation is associated with worse perinatal outcomes, whereas delivery at 40 weeks of gestation results in the best outcomes. 

So do the medical experts recommend inducing mother's to deliver at 40 weeks? Prior to this study, the answer was no. This was simply because of a lack scientific evidence that elective inductions were benefical mother and baby but could instead increase the risk of cesarea sections, infections, seizures, death or other medical conditions. Therefore, the objective of the ARRIVE (A Randomized Trial of Induction Verses Expectant Management) trial was to determine whether elective induction of labor at 39 weeks of gestation (to aim for labor delivery at 40 weeks) would lower the risk of a variety of complications compared to natural-timed delivery in low-risk first time mothers.

### III. OBJECTIVE OF PROJECT
The objective of this project is to:
  1. apply Bayesian methods to determine whether elective induction reduces the occurance C-section and
  2. compare my (Bayesian) findings to those of the ARRIVE trial, which used classical statisical methods

### IV. BAYESIAN ANALYSIS
See the [`notebook`](https://github.com/katannyak/Bayesian_Analysis_C-section_Rates/blob/master/Bayes_project.ipynb) for the analysis.

### V. CONCLUSIONS 
The posterior distributions for the Induction and Management group are shown below with the mean percent (vertical dashed lines) and credible sets (horizontal solid lines) of C-sections. My results from the Bayesian analysis suggests that for first-time mothers who are at term and have no prior condition that makes them at risk for C-sections, they are (slightly) less likely to have a C-section if they proceed with induction. On a personal note, I was interested to do this analysis because I was 40 weeks pregnant at the time. For a post-labor update, I did opt to have an induction at 41 weeks and did not have a C-section.

<img align="center" height="400" src="https://github.com/katannyak/Bayesian_Analysis_C-section_Rates/blob/master/img/posterior3.png">

### VI.REFERENCES
Grobman, WA et al. Labor Induction versus Expectant Management in Low-Risk Nulliparous Women. N Engl J Med 2018; 379:513-523 [paper](https://www.nejm.org/doi/full/10.1056/NEJMoa1800566)
