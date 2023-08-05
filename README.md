# Hierarchical Models Case Study I
Applying a Mixed Effects Model to Predict Movie Popularity

Report
Please limit your write-up to 8 pages in total. Everything you want the grader to read should be included in the main write-up. You will be penalized should your report exceed 8 pages!
Your write-up should specify the statistical model used, including the data model and prior distributions (if relevant), in addition to communicating your analysis findings.
Please type your reports using R Markdown, LaTeX or any other word processor but be sure to knit or convert the final output file to .pdf.
DO NOT INCLUDE R CODE OR OUTPUT IN YOUR SOLUTIONS/REPORTS. R outputs should be converted to nicely formatted tables. Feel free to use R packages such as kable, xtable, stargazer, etc.
All R-code must be included in the appendix. Feel free to also include any supplemental material that is important for your analysis, such as diagnostic checks or exploratory plots that you feel justify the conclusions in your report. Note that you will not be graded on items contained in your appendix and should not assume it will be read.
Reports will be submitted on Sakai
Analysis
Introduction
A film production company wants to know what makes for a successful movie. They have collected box office information about films which released in the US in 2019 as well as some variables they suspect are predictive of box office success. In particular, they wish to know whether a film’s budget and critical score are predictive of it’s net profits. It falls to you to analyze this.

Data
The dataset comes from this kaggle challenge and will be available on Sakai. In addition, it is available on Sakai as United_States_Film_Releases.csv. The provided variables are

Title, the title of the film
Release Date, the date the film was released in mm/dd/yyyy format
Production.Company, the production company or companies which sponsored the film. When multiple production companies collaborate on a film, they are all recorded
Lead.Cast.1, the leading actor/actress in the film
Lead.Cast.2, the second leading actor/actress in the film
Lead.Cast.3, the third leading actor/actress in the film
Director, the director of the film
Box.Office, the amount of money in USD the film made at the box office
Budget, the budget of the film in USD
Run.Time, the run time of the film in minutes
Critic.Score, the IDMB scores of the film
Genre, the genre of the film. Most films are tagged with several genres
Questions of interest
Your job is to investigate whether budget and critical score were predictive of films’ net profits in 2019.

As part of your analysis, explore how the variables provided are, or are not, associated with net profits. Note that you are not given these values directly. One challenge with the dataset is that lots of data are missing: identifying which data are missing and how to handle this are up to you. Moreover, some of the variables are of limited usefulness and may make your models prone to overfitting — few directors directors directed more than one movie, for instance. How to handle or whether to include such variables are another modelling decision.

Be sure to also include the following in your report:

the relationships between net profits and budget as well as net profits and critical score,
the final models you ultimately decided to use,
clear model building, that is, justification for the models (e.g., why you chose certain transformations and why you decided the final models are reasonable),
how missing data was handled,
which variables were included/excluded and why,
model assessment for the final models, the relevant model outputs (table of coefficients with SEs and/or confidence intervals, etc), your interpretation of the results in the context of the questions of interest, including clear and direct answers to the questions posed, and
any potential limitations of the analyses.
Finally, your analysis MUST address the questions of interest directly.
