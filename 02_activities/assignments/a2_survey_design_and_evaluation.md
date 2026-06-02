# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `3`

Describe the purpose of your survey:
```
The purpose of this survey is to gather data for the identification of the effect of age on music taste. The causal direction under investigation is age -> music taste because it does not make sense to consider the causal impact of music taste on age, since age evolves deterministically.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
The target population is the entire population of a country. In this example, consider the country in question to be the United States. The sampling frame can be the respondents to the Panel Study of Income Dynamics (PSID) conducted by the University of Michigan. This frame is convenient for 2 reasons: 1) The PSID sample is selected to be nationally representative on observable demographics, and 2) The PSID is conducted as a panel, so respondents are revisited across sampling periods. This is particularly important for our research question, because we are interested in tracking within-individual changes in music taste at different ages during their lifetime. The sampling unit is an individual. The observational unit is a respondent of the PSID survey. The overall sampling strategy is to conduct stratified random sampling on observable demographics on the PSID sample once, so that our sample is representative of the PSID sample, which is in-turn nationally representative. Then, continue to track the sampled respondents over PSID waves over time, adding units to compensate for drop-outs when necessary.
```

Your 5-10 question survey:
```
1. On the following scale of 1 to 7, please indicate how much you like pop music.
2. On the following scale of 1 to 7, please indicate how much you like rock music.
3. On the following scale of 1 to 7, please indicate how much you like hip hop music.
4. On the following scale of 1 to 7, please indicate how much you like electronic dance music (EDM) music.
5. On the following scale of 1 to 7, please indicate how much you like jazz music.
6. On the following scale of 1 to 7, please indicate how much you like classical music.
7. On the following scale of 1 to 7, please indicate how much you like blues music.
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Cross sectional sample conducted through stratified random sampling.
2. Sample size: 80000
3. Target population: All persons 15 years of age and older in Canada, excluding residents of the Yukon, Northwest Territories, and Nunavut, full-time residents of institutions, and residents of First Nations reserves
4. Sampling frame: Respondents of the 2021 long-form Census of Population
5. Survey mode(s): Interview
6. Timeline: 2023-09-15 to 2024-03-30 (YYYY-mm-dd)
7. Response rate: 40.9%
8. Weights: Weights associated with a unit in the sample are calculated based on province and population groups (demographic groups)
9. Data processing: Social Survey Processing Environment
10. Cleaning, imputation, etc: Donor imputation
11. Sources of error: Imperfect coverage, non-response, response errors, processing errors
12. Limitations, known biases, etc: Bias due to coverage error (small), non-response bias
13. Link to documentation and any additional sources used: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=1526823
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 09 February 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
