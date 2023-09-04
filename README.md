# team-7-bridgestone
Team 7 repo for DS 5380-01 client project

## Quick navigation

[Background](#background)\
[Data](#data)\
[Models](#models)\
[Timeline](#timeline)\
[Repo Structure](#repo-structure)\
[Logistics](#project-logistics)\
[Resources](#resources)\
[Contact](#contact-info)

## Goal
The goal of this project is to develop a demand forecasting model that can accurately predict demand for tire articles in Bridgestone America's (client) inventory for the month of November 2018. The criteria for success as defined by the client is to increase accuracy of predictions versus actual results. 

## Background

Bridgestone is a global tire brand. Its U.S. subsidiary, the client, has tasked us to develop more accurate unit predictions for their tire article inventory for November 2018 to better plan inventory levels. Currently, client's demand planning uses basic rolling averages to set inventory stock levels on a monthly basis, not accounting for trends, seasonality, etc. This approach has led to very little predictive power of actual demand. The client has provided monthly tire unit sales data for the previous 3 years on which we base these predictions.

## Data

The data is provided in pipe-delimited CSV files comprising ~43 GB of data. The data comprises sales tables (of 1 file per month) and four dimension tables named product, store, vehicle, individual. 

The data tables will be joined into one dataset then split into testing and training sets to train and test our models. 

### Data security

The data is propriety client data, therefore, data must be stored securely at all times.

## Models
1. SARiMA
2. XGBoost
3. N-BEATS



## Repo Structure

This repo is structured as follows: Notebooks are grouped according to
their series (e.g., 10, 20, 30, etc.), which reflects the general task
to be performed in those notebooks. Subfiles related to the task (e.g.,
11-, 12-) should be created in order to explore and document necessary,
relevant, or interesting subtasks.

All files which appear in the repo should be able to run, and not
contain error or blank cell lines, even if they are relatively midway in
development of the proposed task. All notebooks relating to the analysis
should have a numerical prefix (e.g., 31-) followed by the exploration
(e.g. 31-text-labeling). Any utility notebooks should not be numbered,
but be named according to their purpose. All notebooks should have
lowercase and hyphenated titles (e.g., 10-process-data not
10-Process-Data). All notebooks should adhere to literate programming
practices (i.e., markdown writing to describe problems, assumptions,
conclusions) and provide adequate although not superfluous code
comments.

## Project logistics

**Meeting times and agenda**: 

| Date/Time | Location | Purpose | Description |
| ------------- | ------------- | ------------- | ------------- | 
| Sundays, [2:00~4:00] | DSI Lounge | Sprint Review / Backlog Grooming / Sprint Planning | In-person meeting to review the current sprint, close all pull requests if possible and establish plans for the next sprint. Create issues for the next sprint. |
| Thursdays, [04:30~05:30]  | DSI Lounge | Coding Session | In-person meeting to review code and trouble-shoot problems/blockers to completing the work. It is important that members come to this meeting after attempting to make progress on their issue(s).|
| Saturdays, by 12:00 PM | Virtual | Submit Issues for Review | Team members will create pull requests for the issues they were responsible for during the week for review by this time. |

**Data location**: Data are stored in the "Data" Folder in this repo. 

**Slack channel**: ds5380_team7 on Data Science MS Workspace

**Zoom link**:
<https://vanderbilt.zoom.us/j/6122882958>

**Project board**:
<https://github.com/orgs/dsi-teams-course/projects/14/>

**Additional information:**
Meetings will generally be held in-person, or over Zoom as schedules/weather requires.
Team members will use the team Slack channel to communicate quick questions, updates, reminders, etc. to the group. 
The team project board will be located on GitHub Project. All project code and comments will live in the team GitHub repo. 

## Resources

-   **Python usage**: Whirlwind Tour of Python, Jake VanderPlas
    ([Book](https://learning.oreilly.com/library/view/a-whirlwind-tour/9781492037859/),
    [Notebooks](https://github.com/jakevdp/WhirlwindTourOfPython))
-   **Data science packages in Python**: [Python Data Science Handbook,
    Jake
    VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/)
-   **Git tutorials**: [Simple
    Guide](https://rogerdudler.github.io/git-guide/), [Learn Git
    Branching](https://learngitbranching.js.org/?locale=en_US)
-   **ACCRE how-to guides**: [DSI
    How-tos](https://github.com/vanderbilt-data-science/how-tos)

## Contact Info

Yuning Wu, M.A. Graduate student\
[yuning.wu\@vanderbilt.edu](mailto:yuning.wu@vanderbilt.edu)

Minwoo Sohn, M.A. Graduate student\
[minwoo.sohn\@vanderbilt.edu](mailto:minwoo.sohn@vanderbilt.edu)

Jordan Nieusma, M.A. Graduate student\
[jordan.m.nieusma\@vanderbilt.edu](mailto:jordan.m.nieusma@vanderbilt.edu)

Ningyu Han, M.A. Graduate student\
[ningyu.han\@vanderbilt.edu](mailto:ningyu.han@vanderbilt.edu)
