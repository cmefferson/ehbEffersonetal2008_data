21 July 2023
Oesdorf, Germany
Charles Efferson

1) The file zurRootSocTD2005.txt includes the completely disaggregated choice data for social learners for Efferson et al (2008), which is "Conformists and mavericks" in Evolution and Human Behavior.

2) What the variables mean:

subject: a unique subject ID for each social learner
chooseRed: a dummy indicating if the social learner chose red in the period in question
noIndRed: the number of individual learners, out of 5, choosing red
statedMajority: a dummy coding if the social learner reporting a general tendency to follow the majority choice among individual learners in a post-exp questionnaire

3) To extract the data used for the model fitting and model selection exercise in Efferson et al (2008), which is based around estimating D (Boyd and Richerson, 1985), remove observations such that (noIndRed == 0 | noIndRed == 5).  See p. 13 of the online supplement to the paper for an explanation of why removing these observations is necessary.

4) To explain a minor inconsistency, the paper says that sessions included 6 blocks of 25 periods each.  If all social learners had completed 150 periods, we would have 6000 observations for social learners.  The paper correctly states, however, that we have 5000 (e.g. Table 1 in paper).  The reason for this discrepancy is the following.  We did not manage to complete 150 periods in all sessions, and for this reason the paper could have been more precise by saying that sessions included UP TO 6 blocks of 25 periods each.  In reality, we have only 100 observations (i.e. 4 blocks) for social learners with ID 47 - 59, and we have only 125 observations (i.e. 5 blocks) for social learners with ID 11 - 24.

I do not remember exactly why we didn't manage to complete all six blocks in all sessions.  I do know that the lab in the Econ Dept in Zurich, which was called the Institut fuer Empirische Wirtschaftsforschung at the time, imposed a non-negotiable upper limit of two hours on sessions.  This upper limit was non-negotiable because this was back in the day when the standard model was to use a student subject pool to run experimentS in an actual physical lab.  The physical lab in Zurich was extremely active at the time, and sessions were really stacked one on top of the other to meet the demands of the many researchers using the lab.

I also remember that, with 150 periods, we were always at risk of bumping up against or even exceeding this upper limit.  So my guess is that some sessions took longer than others to get going, perhaps because participants were somewhat slow to answer control questions, and so we had to end early to avoid exceeding the two-hour limit.