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
The UBC Master of Data Science program is an intensive, professional degree program designed to prepare students for working in the industry. Naturally, landing that next job after graduation is a big focus for many students and discussions around salary expection will likely arise. Tying these ideas together, the question our team in interested in answering with the proposed survey is:

_Does a person's self-rated enjoyment of the MDS program influence their expected salary upon graduation?_

#### Other Questions
<<<<< **[TO DO / FILL IN]** Other questions you plan to ask in your survey to identify confounding variables and justify/explain why you plan to include them >>>>>>>

#### Analysis Approach

1) We will start by conducting exploratory data analysis on the survey results, using statistical summaries and visualization to better see and understand trends in the data.

2) Since our survey will be designed to include questions which identify potential confounding variables, we plan to account for these confounding variables in our statistic analysis via stratification:

> We will form subgroups of survey responses which have the same values of the confounding variables, with special consideration to the sizes of these groups to assess whether there are sufficient observations in each aggregated group.
>
> Then within each stratum, we assess the association between expected annual salary after graduation and self-reported enjoyment of the MDS program. We can do this by fitting a linear model where the response is expected salary and the predictor is the self-reported enjoyment of MDS.

3) We will interpet the results of the linear models across the strata and form a conclusion on the significance and size of the effect of MDS enjoyment on expected salary, having controlled for the confounders.

#### Ethical Considerations

Our survey will remain compliant with the [UBC Office of Research Ethics](https://ethics.research.ubc.ca/sites/ore.ubc.ca/files/documents/Online_Survey-GN.pdf) guidelines. In particular:

* The BC FIPPA act does not allow surveys holding personal information to be hosted in a location other than Canada. Here, "personal information" is defined as information that is directly identifying, or may be used in conjunction with other identifiers to identify an individual (ex. Student Number, IP Address, etc). Although our survey does not intend to ask for information that could be directly identifying, our group decided to hold use the UBC hosted version of Qualtrics as a precaution. 

* Although we have curated our questions and do not believe them to be too specific, we may still end up receiving a single response in a category. In the event that this happens, we will suppress the information to keep responses anonymous.

* As our survey will be online, participants also need to agree to a cover letter to provide consent. Our cover letter will be as follows: 

> MDS Salary Survey - 
>
> The following questionnaire aims to gather information on how the MDS program shaped salary expectations for MDS students following graudation. Survey results will be provided after analysis to all MDS students. Participation is optional, responses are anonymous, and any information obtained in this survey will be kept confidential. 
>
> If you have any concerns or complaints about your rights as a research participant and/or your experiences while participating in this study, contact the Research Participant Complaint Line in the UBC Office of Research Ethics at 604-822-8598 or if long distance e-mail RSIL@ors.ubc.caor call toll free 1-877-822-8598.
>
> If you have any questions for the research group, we can be contacted here: 
>
> Alex Pak - [pak-alex](https://github.com/pak-alex) <br/>
Carrie Cheung - [carrieklc](https://github.com/carrieklc) <br/>
Evan Yathon - [EvanYathon](https://github.com/EvanYathon) <br/>
Talha Siddiqui - [talhaadnan100](https://github.com/talhaadnan100)
>
> By completing the questiionnaire, you are consenting to participate in this research. 