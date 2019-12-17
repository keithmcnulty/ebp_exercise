# Exercise for Evidence Based Practice session  - 20 November 2019

You are working for a North American sales company that has offices in six locations.  Recently the CEO of this company
has become interested in the performance of its managers.  She is interested in knowing what measurable factors influence
whether or not a manager performs well or performs poorly.


## Data available

The data available includes the following fields for 571 managers:

* `employee_id` for each manager
* `performance_group` of each manager: Bottom performer, Middle performer, Top performer
* `yrs_employed`: Total length of time employed in years
* `manager_hire`: whether or not the individual was hired directly to be a manager (Y) or promoted to manager (N)
* `test_score`: score on a test given to all managers
* `group_size`: the number of employees in the group they are responsible for
* `concern_flag`: whether or not the individual has been the subject of a complaint by a member of their group
* `mobile_flag`: whether or not the individual works mobile (Y) or in the office (N)
* `customers`:  the number of customer accounts the manager is responsible for
* `high_hours_flag`: whether or not the manager has entered unusually high hours into their timesheet in the past year
* `transfers`: the number of transfer requests coming from the manager's group while they have been a manager
* `reduced_schedule`:  whether the manager works part time (Y) or full time (N)
* `city`:  the current office of the manager.

The data is available in an RData file (which ensures the data types are correct), or a csv file, where you may need to convert to the correct data types.  Choose whichever you prefer to work with.

## Your task

Work on this data in groups of three.  Using whatever method you deem appropriate, try to determine:

1.  Which variables have an effect on manager performance?
2.  For those variables which have an effect, how 'strong' is the effect?
3.  What might be an explanation for such effects?
4.  What are the limitations of your analysis?

If you are unsure about an approach to take to the analysis, Keith will be available to provide advice and suggestions.  If you source the file `logistic_regression.R` this makes a function available to you which could be useful, and allow you to generate results pretty quickly.   

**This exercise is not about the technical approach**.  It is important not to spend too much time on this.  The purpose of this exercise is to expose the group to the typical challenges of communicating analytical results to a non-expert audience.  Be prepared to present and explain your results to an audience of mixed experience in analytics, and to facilitate a discussion around them.  Do not invest a lot of time in graphs or pretty displays - simple bullet points indicating your conclusions supported by statistics will suffice.

Good luck!