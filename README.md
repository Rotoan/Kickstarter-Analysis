# Kickstarting with Excel

## Overview of Project
This is a quantitative analysis of Kickstarter projects for theater plays. Outcomes are sorted based on
the fundraising goals of each project, as well as the month in which each was launched.

### Purpose
This analysis is intended to project common characteristics of successful or failed Kickstarter
theater projects, to assist the launching of a new campaign for a theater project on Kickstarter.


## Analysis and Challenges
Analysis was performed by breaking down theater projects based on the month in which they launched, obtaining
counts of how many successful and failed campaigns launched in each month.
[Outcomes by Launch Month](resources/theater_outcomes_vs_launch.png) This count shows a strong correlation
between the month in which a campaign was launched and the eventual  odds of its success. This metric does not, 
however, take into account any changes in trends over the several years since Kickstarter was launched. It also 
does not capture any underlying attributes about those projects or their relative worthiness of fundraising.

Further analysis was performed by breaking down the successful percentage of completed theater fundraisers
based on the declared fundraising goal of each project.
[Outcomes by Goals](resources/outcomes_vs_goals.png)This comparison of outcomes evaluated the balance of
successful versus failed fundraisers for projects within different goal ranges, from under 1,000$ to over 50,000$.
This metric does not take into account by what amount a project was over or under its goal, nor does it reveal
any underlying information about the worthiness of these projects.



### Analysis of Outcomes Based on Launch Date
[Outcomes by Launch Month](resources/theater_outcomes_vs_launch.png)
It appears from this analysis that the most successful month for launching a theater Kickstarter campaign
is May, though the late spring and early summer perform better than the rest of the year as a whole. Furthermore,
projects launched in the fall and particularly September through November are much more likely to fail.

### Analysis of Outcomes Based on Goals
[Outcomes by Goals](resources/outcomes_vs_goals.png)
From this breakdown of the ratio of successful and unsuccessful fundraising campaigns at different goal
brackets, a few points stand out. Projects with goals less than 10,000$, particularly those under 5,000$, and those
with goals between 35,000$ and 45,000$ are subtantially more likely to be successful than projects with goals for
any other amount. Particularly unsuccessful are those with goals between 20,000$ and 35,000$ or more than 45,000$.

### Challenges and Difficulties Encountered
This data set is limited by the lack of underlying metrics of the worthiness of any particular fundraising project.
This can be inferred to some extent by whether projects were endorsed, or by the average size of pledges.
Further analysis could be performed breaking down results by year, to indicate any directional trends as Kickstarter
develops as a commonly used platform.


