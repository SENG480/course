---
Title:  Documenting and Understanding Software Systems
Subtitle: CRN 2366{2,3,4} - SENG 480A/CSC485A/CSC578B - A01
Author: Neil Ernst
---

# Schedule and Topics - Spring 2017

The following schedule is subject to change, and will change.

| Class  | Topics | Other Resources | Readings  | Deadlines |
| ------ | --------------------------------------------------------- | --------- | ---------------- |------- |
| Jan 4  | Intro; introductions; Project outlined. [What is Software Architecture](https://github.com/SENG480-18/course/blob/master/lectures/1-intro.md)? | | text chapter 1 | |
| Jan 8  | [Software arch overview](https://github.com/SENG480-18/course/blob/master/lectures/2-arch.md). | | text chapter 2 | |
| Jan 11 | [Reading Code.](https://github.com/SENG480-18/course/blob/master/lectures/3-reading.md) | | chapter 3 text, source code of [web crawler]( https://github.com/aosabook/500lines/tree/master/crawler/code) | | 
| Jan 15 | [Architecture Stakeholders and Requirements](https://github.com/SENG480-18/course/blob/master/lectures/4-req.md). Team kickoff | | text chapter 16  | **M0 due** |
| Jan 18 | More on Requirements and Scenarios • Project work |||
| Jan 22 | [Views on Architecture - Modules](https://github.com/SENG480-18/course/blob/master/lectures/5-modules.md) | | text chapter 18 | **M1 due** |
| Jan 25 | [Views part 2 - C&C](https://github.com/SENG480-18/course/blob/master/lectures/6-cc.md) | [SEI view example](https://wiki.sei.cmu.edu/sad/index.php/OPC_Module_Uses_View) | text chapter 4 | | 
| Jan 29 | [Architecture and Design](https://github.com/SENG480-18/course/blob/master/lectures/7-design.md) | [What is Architectural Design](http://www.informit.com/articles/article.aspx?p=2738304&seqNum=2) | text chapter 17 | |
| Feb 1  | Design cont. ||| **M2 due** | 
| Feb 5  | [Documenting behavior.](https://github.com/SENG480-18/course/blob/master/lectures/8-behavior.md) [*Technical writing skills (30 mins)*](https://github.com/SENG480-18/course/blob/master/lectures/Technical%20Writing%20FINAL.pptx)  | | [SEI behavior tech report](http://repository.cmu.edu/cgi/viewcontent.cgi?article=1680&context=compsci) | |
| Feb 8  | Mid-term project status updates | | || 
| Feb 11 | | | |  **assignment 1 due midnight** | 
| Feb 12 | Reading Break | | |
| Feb 15 | Reading Week | | |
| Feb 19 | Group work in class - Omar leads | | | **M3 due** |
| Feb 22 | Class cancelled - Neil away | |  | |
| Feb 26 | Midterm | | | **Midterm** |
| Mar 1 | *Industry lecture - model driven development* | | |
| Mar 5  |  API and Interface documentation. User centric docs. | | [Interface documentation](https://resources.sei.cmu.edu/asset_files/TechnicalNote/2002_004_001_13973.pdf) |  **M4 due** |
| Mar 8 | Microservice styles. | || |
| Mar 12 | Documenting Ops | | <!--RW text has chap 21 ; allocation views; Len's book --> |
| Mar 15 | Architecture analysis | | ch 21 | |
| Mar 19 | Architecture analysis | | ch 21 | **M5 due** |
| Mar 22 | *Industry lecture - agile teams and architecture* | | |
| Mar 26 | Technical debt | | | |
| Mar 29 | (float) | | | |
| Apr 2 | Project presentation | | | |
| Apr 5 | Project presentation | | | **M6 and M7 due in repo**  |
| Apr 10 | No class ||| **Grad report due** |

# Syllabus
Software is a long-lived and complex thing. This course is about understanding software in the large. We use the SEI text as a framework for understanding large-scale software systems. Topics include

* what is architecture? Who are architects?
* what structures are important to understand?
* views on software systems
* software quality attributes
* architecture analysis and recovery
* architecture-driven design
* agile architecture
* design, architecture, and technical debt

(the official course syllabus is [distributed via HEAT (SENG480a link)](https://heat.csc.uvic.ca/coview/outline/2018/Spring/SENG/480A))

## Required Text:
SEI Software Architecture in Practice, Len Bass, Paul Clements, Rick Kazman. 3rd Edition. 2013.

### Other texts
* Design It! From Programmer to Software Architect, by Michael Keeling, Pragmatic Programmers 2017.
* Just Enough Software Architecture, by George Fairbanks, Marshall and Brainerd, 2010.
* Documenting Software Architectures, by Paul Clements et al., Addison-Wesley, 2011.
* Designing Software Architecture, A Practical Approach, by Humberto Cervantes and Rick Kazman, Addison-Wesley 2017.
* Software Systems Architecture: Working with Stakeholders Using Viewpoints and Perspectives, by Nick Rosanski and Eoin Woods, Addison-Wesley, 2011.
* Applied Software Architecture, Christine Hofmeister, Rod Nord, Dilip Soni, Addison-Wesley, 2000. 
* Essential Software Architecture, by Ian Gorton, Springer, 2011.
* Software Architecture: Perspectives on an emerging discipline, Mary Shaw and David Garlan, Prentice-Hall, 1996.
* Architecture of Open-Source Applications, Amy Brown and Greg Wilson, eds. http://aosabook.org

## Past versions:

* past deliverables, similar in form to what this course will produce,  from the TU Delft IN4315 course, are available at https://delftswa.github.io and https://www.gitbook.com/@delftswa. These are both modeled on the AOSA book -- http://aosabook.org

## Instructors

* [Neil Ernst](http://neilernst.net), instructor. Office ECS 560, office hours after class Thursday or DM me.
* Omar Elazhary, teaching assistant

# Course Overview

After the course, students are able to:

* begin to reason about and evaluate software design tradeoffs
* capture software architecture in modern documentation approaches
* work together in teams, with modern software tools.
* use a views and beyond approach to capture software architecture.
* compare and contrast different architectural styles, including product lines, microservices, MVC.
* explain and recognise technical debt.

# Deliverables
The class will use [Github](https://github.com/SENG480-18) and [Slack](https://seng480-s18.slack.com) to work on the project. Students will have to register their Github username (either a permanent one or a throwaway) with the instructors. Those with an objection to using Github please contact the instructor for workarounds. All Github activity is private to the class organization. Please see the privacy notice on the Connex site.

[Slack](https://seng480-s18.slack.com) will be the primary mechanism used for communication in the class. My rationale (apart from being tools used in practice) is to expose the class as a whole to questions about projects, assignment, and lectures. 

University and department policies on professional conduct and integrity are applicable. Feel free to see me in person, or via UVic email, for personal questions.

## Overview
There is one assignment, a midterm, and a substantial group project. Grad students have one extra assignment to conduct. 

## Assignment
*Undergrads*: One individual assignment worth **25%** of final mark. Due dates as below. 

- for one of the projects in the course, pick a quality attribute, create a quality attribute scenario, and document how the project source code realizes this scenario. Provide discussion on how the project can handle changes in this scenario in the future.

*Grads*: the undergrad assignment, plus 

- a documentation review session on the student document, with report detailing how well the documentation has been completed (e.g., can we answer key stakeholder questions).

## Group Project
The primary deliverable is a group project. You and your team will select a software project (OSS on Github), and document important views on the software. The end result will be a set of documentation about the software system and a deep understanding of how it is constructed. **60%** of final mark. Students will be assigned to teams and document an open source software system. Due dates in calendar below. See [the Project outline](https://github.com/SENG480-18/course/blob/master/project.md).

## Midterm
One midterm, worth **15%**. Tentatively scheduled for Feb 26.

## Final
No final.

# Resources

1. [Slack](https://seng480-s18.slack.com)
2. [Github site](https://github.com/SENG480-18)
2. [Github help pages](https://help.github.com)
3. [Github bootcamp](https://help.github.com/articles/set-up-git/)

