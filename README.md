# "The Last Supper": Trying to predict the viability of San Francisco restaurants with Machine Learning and data analysis

## 1. Background
### 1.1 Problem or Opportunity Statement
Briefly describe the analytic problem.
What are critical factors to the probability of a restaurant closing down in a city?
Our objective is to create a predictive model, based on a set of criteria, to determine which restaurants in San Francisco are most likely to close within a determined period of time (ex: within a year).
### 1.2 Service Implementation
Briefly describe the service implementation that will result from the analysis. How will you implement the analytic work?
We seek to create a predictive regression model which we will visualize with a dynamic map, showcasing spatial patterns and trends, as well as individual restaurant location with descriptive attribute data (name, address, yelp review page etc.). We intend to implement a Machine Learning component by feeding the model with updated API data so that the prediction remains relevant with up-to-date data.
### 1.3 Business Case
Briefly describe why we should solve this problem. Is something broken? Is it urgent? If we do it now, does it help us down the road? What are the consequences if we don’t do it? What is the value if we do it?
The vast majority--90%--of independently owned restaurants in the United States close within a single year(1). Thus enterprising restaurateurs would benefit to understand the odds and opportunities of a given prospect location for a future restaurant. We also wish to test whether social media such as Yelp Reviews have a significant bearing toward the long-term viability of a restaurant.
The nature of restaurant  turnover rate is also one of its relationship with the space it occupies and serves; we posit that understanding what makes a restaurant’s success or failure can be indicative of changes within a neighborhood, be it cultural, demographic, or economic.
Along with geographic location, health safety is a important variable in a restaurant. We will look at how the health score impacts the viability of a restaurant’s longevity.
1- http://www.perrygroup.com/foodservice-expert-overview-on-how-long-restaurants-last/

## 2. Project Vision, Deliverables and Scope
### 2.1 What does success look like
Briefly layout a vision of what a successful result looks like.
A statistically significant and accessible predictive model that can read intuitively by a non-statistically minded general audience, reflecting the reality of the restaurant business in San Francisco, and iteratively refined via up-to-date data from API sources.
### 2.2 Deliverables
What are the specific deliverables that will result in or lead to the vision, e.g. a model, decision aid. Note: these may change throughout the course of the project.
The deliverables are as defined:
A concise 15 minutes presentation designed for a technically minded and critical audience;
A live site hosting a descriptive thematic background, a map/data visualization model, and a methodology walkthrough of the project;
A GitHub repo that is concise and legible, so that our model may be replicated and expanded upon by anyone who wishes to do so.
### 2.3 Scope
What will the project consist of? What systems, datasets, business processes or staff will it involve? What subgroups, categories or areas of interest are in scope? What is out of scope? 
The maximum duration of the final project engagement is until presentation day on the 8th of August 2018 and the scope should be appropriate for that time period.
![alt text](https://github.com/HP-Nunes/final-project-ml/raw/master/img_finalproj.png "roadmap mock-up")
## 3. Project Planning
### 3.1 Roles and Responsibilities
Who needs to be involved and why.

| **Role** | **Responsibility** |
| --- | --- |
|   |
| Project Admin | Responsible to keep all members informed and involved on project progress; makes sure the agreed deadline and timetables are respected; facilitates meeting agenda and prepare notes shared on the group&#39;s preferred communication platform. |
| Subject Matter Expert | Provides insight into relevant implementation processes, data and workflows; provide input on model output, testing and implementation; keeps relevant and accessible notes on bugs and technical challenges;responsible for contextual thematic research. |
| Database Admin | Understands the databases and how to extract data from them. Responsible for ensuring data is extracted and available for both the analysis and implementation phase. Understands the structure of the data and if a relational database, can explain the data design. Can respond to questions about changes in the database over time. |
| GitHub Admin | Project&#39;s GitHub owner, is responsible maintaining the project&#39;s Git up-to-date, and to back-up the project&#39;s data and code on a local machine AND external drive. |
| &quot;Stakeholders&quot; | List anyone else who will be affected by the work or require input into the work and how we should engage them. |
### 3.2 Project Phases
What are the key phases and outputs of the project? Below are the default phases for a DataScienceSF project.

| **Phases** | **Description** | **Responsible Party** | **Output(s)** |
| --- | --- | --- | --- |
| Project Planning and Preparation |
| Project Charter and Planning | Before beginning work, we complete and sign this document. | Project Admin | Signed charter |
| Data Access | Pull and deliver relevant data to the project. The Database Admin must provide an overview of the data structure. | Database Admin | Data Access; Confidentiality agreement if needed |
| Data &amp; Business Knowledge Transfer | Provides data documentation and other program or business process documentation. | Subject Matter Expert | Existing business documentation; additional notes/documentation if needed; any research reports or prior analyses |
| Iterative Analysis: Analysis, Review, Service Plan |
| Context and User Research | SMEs and frontline staff provide overview of current process or workflow; DataSF staff will observe, interview, etc as needed to understand business process and implementation alternatives. |   | Research Summary; Implementation Plan; Output design |
| Exploratory Analysis | Exploration of data and summary data |   | Exploratory Analysis Briefing |
| Model Build Out | Model build out (meet as needed to flush out model details) |   | Model and Briefing |
| Model Evaluation | Model evaluation (compare to status quo using training data set(s)) |   | Model test results |
| Implementation Pilot &amp; Iterative Analysis | Department is available to help test or implement test of model and output as part of updated business process or workflow; Feedback from testing is used to tweak model and output |   | Pilot results; Updated model(s) |
| Project Close out |
| Final Model and Handoff | Full implementation of model and output into current process; Training and knowledge transfer to Department |   | Final model; Final output; Long term testing plan |
| Documentation and Dissemination | Write up description for project library and slidedeck for demo day; may include blog post or article to share with larger community | | Demo Day deck, project library write up; Others as needed |

### 3.3 Project Milestones
What are the key milestones that will demonstrate progress? Preemptively calendar key in-person check-ins and recurring phone calls.

| **Milestone** | **Responsible party** | **Completion Day** |
| --- | --- | --- |
| Project Kick Off Meeting (In-person) | Project Admin | J-21 (Wed. July 18th) |
| Project Charter drafted | Project Admin | Between J-21 &amp; J-17 |
| Project Exploration | Database Admin | J-15 |
| Exploratory data analysis briefing | Database Admin | Between J-15 &amp; J-13 |
| ML modelling and exploration of methodologies | Subject Matter Expert | Between J-13 &amp; J-5 |
| Live implementation |   | J-7-J-0 |
| Presentation Roles Assigned; Presentation Draft |   | J-7 |
| Presentation Run-Through #1 |   | J-4 |
| Presentation Run-Through #2 |   | J-1 or J-2 |
| Presentation Day | All | J-0 |
| GitHub Repo Clean with Concise Read-Me; live online implementation | All | J-0 |
| Postmortem | Project Admin | J-0 |

### 3.4 Constraints, Assumptions, Risks and Dependencies

**Constraints.** Include any constraints related to the project, for example:
- time
- staffing and resources
- budget
- deadline for completion
- availability of detailed or complete information
- data
- methods
- conflicting interests/projects within team
- technology and availability of specific tools or hardware
- legal etc

### 3.5 Success measures / ROI
_What specific measures should we use to measure success or return on investment (ROI). How will these measures be tracked before and after the implementation? Describe any existing costs or time measures that you expect to be impacted. It&#39;s helpful to structure this as the expected result: e.g. save staff x number of hours, increase revenue by x, increase number served by y, etc. Alternatively, try describing the story of success._

---
## Team

[Hadrien Picq](https://github.com/HP-Nunes)

[Daniel Tang](https://github.com/dtang29)

[Charlie Fortuno](https://github.com/c42know)

[Alex Pundyk](https://github.com/apundyk)


## Acknowledgement

Our instructor [Dani Roxberry](https://github.com/droxey)

@kataquino 

@PeterGardner

[@spatialai](https://twitter.com/spatialAI) & Griffin Moris for providing aggregated social media profile data.



