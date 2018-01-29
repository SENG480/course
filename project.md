---
Title: Project Requirements
Author: Neil Ernst 
---

# Overview
The course project is a semester long effort to apply the ideas behind code reading and communication to a realistic project.

Your team gets to choose the project you will work on (subject to some restrictions). In general the project must be *active* (daily commits), *moderately large* (>100 stars on GH, but not intractably complex), and *open-source*. Since other teams have done this type of course, you cannot select from the [banned project list](https://github.com/SENG480-18/course/blob/master/banned.md). This is to avoid annoying hard-working and under-compensated OSS maintainers.  

## Milestones

- **M0.** team formation and Github (5%)
- **M1.** identify project stakeholders and business goals (5%)
- **M2.** identify architecturally significant requirements and utility tree (10%)
- **M3.** module view (20%)
- **M4.** C&C view (20%)
- **M5.** assess project code quality and technical debt (15%)
- **M6.** present report in class, deliver final chapter proof-edited and well organized (10%)
- **M7**: using your knowledge of the project, submit a pull request that improves the project. (15%)

## Teams

- Instructor assigned - see Slack
- If you are having trouble with your team (lazy group members, poor communication, technical trouble, etc.) **come see me or Omar as early as possible**. We cannot help you if you don't let us know. Telling me in April that the team was not effective will not be an excuse.
- A regular meeting schedule is highly recommended to keep everyone on track. You might want to follow a [Scrum style standup](https://www.mountaingoatsoftware.com/agile/scrum/meetings/daily-scrum): each team member says:
    -   What did you do since last meeting?
    -   What will you do before the next meeting?
    -   Are there any impediments in your way?
- You can organize how you wish, but everyone must contribute, and one person should be in charge of overall planning. 

All students are expected to participate equally in discussions, design and development. The instructor will make marking adjustments for individual students where this participation has not occurred; this may result in a failing grade for the project. At the mid-point and conclusion of the project you will be asked to evaluate your colleagues on the team. Your peer review score and participation on Github/Slack will strongly influence what percentage of the project mark you get. 

# Formats and Logistics
The final team deliverable is a *book chapter* that we will publish on [Gitbook](https://www.gitbook.com/). Gitbook accepts both Markdown and ASCIIdoc; both of these are described on [the Gitbook help pages](https://toolchain.gitbook.com/structure.html). You will write the submissions in a Github team repository with standard text editors. Markdown and ASCIIdoc editors are also plentiful. I like [Byword](https://bywordapp.com) and [Marked](http://marked2app.com). 

Your final presentation will be an architecture presentation, of the system you chose, to the entire class. Keynote/Powerpoint etc are suitable here. 

# Milestones
Note that since we are *documenting and communicating*, good technical writing practices (spelling, grammar, organization, clarity) are always required and will be subject to lost marks if not followed. You can always reach out to the [Center for Academic Communication](https://www.uvic.ca/learningandteaching/home/home/centre/index.php) if you need extra assistance.

## 0. Github (5%)
### Deadline
Jan 15.

### Deliverables
- Create a repository using the Github Classroom link
- send your Github IDs to Omar
- update the Readme with your team's name, and 3 projects of interest.

### Marking Guide
Simple. Do the above for full marks.

## 1. Identifying project stakeholders and business goals (5%)
This deliverable will serve as an introduction to the project you have chosen to focus on. You will read project documents and related material (e.g., StackOverflow) to get a sense for who the stakeholders are, and what the project wants to accomplish.

### Deadline
This is due in Github **midnight Jan 22.** 

### Deliverables
1. Identify stakeholders for the system you chose. Complete a [stakeholder profile table](https://www.viewpoints-and-perspectives.info/home/stakeholders/):
2. Create a list of business goals (see chap 16) for this system. We will use those in M2 as well.

### Marking Guide	
- completeness and relevance of stakeholders.
- properly thought out business goals, based on empirical data (project docs, tech pubs, etc.)

## 2. Architecturally significant requirements (ASRs) and utility tree (10%)

### Deadline
Due in Github by **Feb 1**

### Deliverables
1. The list of ASRs
2. A fully worked out utility tree, with at least 7 prioritized quality attribute scenarios, 3 (of the 7) in template form.

### Marking Guide
- Relevance of the ASRs to the project. 
- Appropriateness of scenarios.
- Quality of scenarios.

## 3. Module View (20%)

### Deadline
Due in Github by **Feb 19**.

### Deliverables
A fully worked module view according to the SEI view templates. Includes interface and behavior documentation.

### Marking Guide

## 4. Component and Connector View (20%)

### Deadline
Due in Github by **March 5**.

### Deliverables
A fully worked C&C view according to the SEI view templates. Includes interface and behavior documentation.
### Marking Guide

## 5. Code Quality and Technical Debt (15%)
Assess your project's code quality using automated tools like BetterCodeHub, Sonarqube, CodeScene.

### Deadline
Due in Github by **March 19**.

### Deliverables
1. Code quality report.
2. Based on your architecture documents, analyze potential technical debt in the project. Report at least 3 potential shortcuts that might have long-term consequences.

### Marking Guide

## 6. Final Presentation and Report  (10%)
In class presentation of ~15 minutes; final report polished and cleaned up (e.g. add introduction, conclusions, references).

### Deadline
Due in Github by **Apr 6**. Presentation in class either Apr 2 or 5.

### Deliverables
Use the GitBook toolchain to ensure your chapter compiles to something readable on the site. 

Presentation must be attended by all group members, all of whom may be asked questions about the project.

### Marking Guide
* Presentation organization
* Presentation competently run
* Presentation on time.
* Report compiles to PDF/Gitbook
* Report has all necessary sections.
* Report has fixed comments from previous submissions.

## 7. Pull Request (15%)

### Deadline
Due in Github by **midnight Apr 6**.

### Deliverables
Link to a pull request for your case study, showing an improvement.

### Marking Guide
Silly or trivial pull requests will lose marks. It does not have to be complex, but does have to demonstrate you understand the project and are not just annoying the maintainers.

# Educational Objectives


# Helpful Links
* [Student's Guide to SE projects](http://www.cdf.toronto.edu/~csc301h/fall/csc301.pdf) 
* [Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [GWT](http://www.gwtproject.org/doc/latest/tutorial/index.html)
