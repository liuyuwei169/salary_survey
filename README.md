# MDS Salary Survey Study

## Contributors

|Team Member|GitHub Handle|
|-----------|-------------|
|Alex Pak|[pak-alex](https://github.com/pak-alex)|
|Carrie Cheung|[carrieklc](https://github.com/carrieklc)|
|Evan Yathon|[EvanYathon](https://github.com/EvanYathon)|
|Talha Siddiqui|[talhaadnan100](https://github.com/talhaadnan100)|

## Project Proposal

#### Motivation and Primary Question
The UBC Master of Data Science program is an intensive, professional degree program designed to prepare students for working in the industry. Naturally, landing that next job after graduation is a big focus for many students and discussions around salary expectation will likely arise. Tying these ideas together, the question our team in interested in answering with the proposed survey is:

_Does a person's self-rated enjoyment of the MDS program influence their expected salary upon graduation?_

#### Other Questions
<<<<< **[TO DO / FILL IN]** Other questions you plan to ask in your survey to identify confounding variables and justify/explain why you plan to include them >>>>>>>

#### Analysis Approach

1) We will start by conducting exploratory data analysis on the survey results, using statistical summaries and visualization to better see and understand trends in the data.

2) Since our survey will be designed to include questions which identify potential confounding variables, we plan to account for these confounding variables in our statistic analysis via stratification:

> We will form subgroups of survey responses which have the same values of the confounding variables, with special consideration to the sizes of these groups to assess whether there are sufficient observations in each aggregated group.
>
> Then within each stratum, we assess the association between expected annual salary after graduation and self-reported enjoyment of the MDS program. We can do this using an ordinal linear regression where the response is expected salary and the predictor is the self-reported enjoyment of MDS.

3) We will interpret the results of the linear models across the strata and form a conclusion on the significance and size of the effect of MDS enjoyment on expected salary, having controlled for the confounders.

#### Ethical Considerations
<<<<< **[TO DO / FILL IN]** Discuss the aspects of the UBC Office of Research Ethics document on using Online Surveys that are relevant to your proposed survey. >>>>>
