Instituto Superior Técnico, Universidade de Lisboa

**Network and Computer Security**

# Project Overview

This document describes the organization of the project for the Network and Computer Security / Segurança Informática em Redes e Sistemas (SIRS) course.

The document concludes with a calendar containing all the deadlines.

For any questions regarding this document, please contact:  
[meic-sirs@disciplinas.tecnico.ulisboa.pt](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)

# 1. Introduction

The SIRS (Network and Computer Security) course requires a practical project dealing with security solutions.  
The whole process is organized in 10 sequential stages:

| **Stage**                                                       |
| ----------------------------------------------------------------|
| [1. Assemble team](#21-assemble-team)                           |
| [2. Pick topic](#22-pick-topic)                                 |
| [3. Write proposal](#23-write-proposal)                         |
| [4. Await approval](#24-await-approval)                         |
| [5. Develop project](#25-develop-project)                       |
| [6. Prepare demonstration](#26-prepare-demonstration)           |
| [7. Write report](#27-write-report)                             |
| [8. Submit code and report](#28-submit-code-and-report)         |
| [9. Check presentation session](#29-check-presentation-session) |
| [10. Present and defend](#210-present-and-defend)               |  

<br />

# 2. Stages

Each stage is described in the following sections.

## 2.1. Assemble team

Assemble a team of 3 students, committed to work together.  
Inform the lab professor of the group members.

## 2.2. Pick topic

The topics for the project are described in another document, which will be posted on the web site.

Read the scenarios descriptions and, as a group, sort the topics by preference for doing your work.
Apply for a topic when the selection page opens.
Each group should be represented by one student only.

In the selection form, identify your group as `CXX`, where `C` is replaced by A(lameda) or T(aguspark) and `XX` is replaced by the two digits of your group number, as assigned by Fénix.
For example, group 22 of Taguspark is T22 and group 7 of Alameda is A07.

Also in the form, sort all the topics by order of preference.
Number 1 will be your most preferred topic.

There are limited vacancies per project topic and slots will be assigned on a _first-come-first-served_ basis.

IMPORTANT: check the deadlines table for the topic selection opening and closing dates.

The official topic selection list will be posted after the process is concluded, to confirm the topic assigned to each group.

## 2.3. Write proposal

After having a topic assigned, your group should prepare a proposal document.
The project proposal should describe the problem and the proposed solution.

You can bring a draft of the proposal to your lab session or office hours to present it and receive feedback.  

### 2.3.1. Technical core requirements

The planned project will need to have, _at least_:

- a set of separate (virtual) machines, with network isolation;
- a secure communication tunnel (e.g. TLS, SSH) using correct configuration;
- the design and deployment of one mechanism using a custom security protocol.

### 2.3.2. Document requirements

- PDF format;
- Mandatory file name `CXX_WWW_HHMM_L_proposal.pdf`
(where `C` is A for Alameda, T for Tagus, `XX` is the Fenix group number with two digits, `WWW` is the weekday of the lab shift – Mon, Tue, Wed, Thu, Fri – `HHMM` is the time – Hours and Minutes – and `L` is the lab room number);
- Report cover: Project title. Headed by course name, group campus, group number.
In the next row: group members sorted by ascending student number.
For each student, include the number, name and professional photo with face clearly visible;
- Report body: The font should be no smaller than 11pt, with standard line and character spacing;
- Limit of 4 pages (excluding cover);
- Pages should be numbered (preferably with a label like `Page X of Y`);
- The use of UML diagrams (or other standard notations) is recommended for clear and concise communication.

### 2.3.3. Document structure (mandatory)

1. Problem  
_Given the chosen scenario, where is security necessary?_  
_What is the main problem being solved?_  
Use around 200 words.  
  1.1. Solution Requirements  
  _Which security requirements were identified for the solution?_  
  Present as a list.  Identify each requirement with R1, R2, ...  
  1.2. Trust assumptions  
  _Who will be fully trusted, partially trusted, or untrusted?_  
  Write down the trust relationships to make them explicit.  
2. Proposed solution  
  2.1. Overview  
  _What are the main components of the solution? How do they relate?_  
  Diagram and explanation with, at most, 200 words.  
  If you do not use UML or another standard notation, include a legend.  
  2.2. Deployment  
  Describe distinct machines and how they will be interconnected.  
  2.3. Secure channel(s) to configure  
  _Who will communicate?_  
  Identify communication entities.  
  _What existing security protocol will be used?_  
  Choose existing TLS or SSH library/tool to use.  
  _What keys will exist and how will they be distributed?_  
  2.4. Secure protocol(s) to develop  
  _Who will communicate?_  
  Identify communication entities and the messages they exchange with a sequence or collaboration diagram.  
  _Which security properties will be protected_?  
  Identify the security properties to ensure.  
  _What keys will exist and how will they be distributed?_  
3. Considered technologies  
  Succinctly describe the technologies that are being considered, e.g., programming languages, frameworks, libraries, tools, etc.
4. Plan  
  4.1. Milestones  
  Describe _basic_, _intermediate_ and _advanced_ versions of the work and when are they expected to be achieved.  
  The basic version is the minimum security functionality.  
  The intermediate version includes the most important security mechanisms.  
  The advanced version should address more attacks.  
  4.2. Effort commitments  
  Include a Gantt chart describing the planned tasks and how much time is allocated to the implementation  
  (for example, consider a total of ~180 Person/hour, i.e., 3 weeks for a team of 3 people, each with 50% allocation of a 40-hour work week).  
  This Gantt chart should illustrate the tasks for the different milestones and the expected conclusion date for each.  
5. References  
  Bibliographic references cited in the project proposal.  

## 2.4. Await approval

The proposal document will need to be approved by the course faculty.

## 2.5. Develop project

Develop basic, intermediate and advanced versions over the project weeks.

Attend the lab sessions to present your ongoing development and receive early feedback from the professor.
A security project that receives regular feedback can be improved earlier and is more likely to achieve a better result.

## 2.6. Prepare demonstration

IMPORTANT: once your team achieves the intermediate version of the work, start preparing the demonstration.

Write a `README` file with step-by-step instructions on how to run your project
(suggested [README template](https://gist.github.com/miguelpardal/36f6ef7864bfdeabe5c57b161aa80f2f)).  
Record screenshots, screencasts or similar artifacts showing your project in action.

## 2.7. Write report

The project final report should describe the problem and the implemented solution, along with a presentation of the results.
The report document should update and extend the proposal document to reflect what was actually achieved.

### 2.7.1. Document requirements

- PDF format;
- Mandatory file name `CXX_WWW_HHMM_L_report.pdf`;
- Report cover;
- Report body: The font should be no smaller than 11pt, with standard line and character spacing;
- Limit of 5 pages (excluding cover), plus 2 pages for Annexes if necessary for reference materials;
- Pages must be numbered (preferably with a label like `Page X of Y`).

### 2.7.2. Document structure (mandatory)

Same as the proposal, with the following differences:

- Replace _Considered Technologies_ with _Used Technologies_: state what was actually used;
- Replace _Plan_ with _Results_: state what was actually achieved. For each requirement - R1, R2, ... - state if it was satisfied, partially satisfied, or not satisfied; with a brief justification for each one.
Justify main implementation choices.

## 2.8. Submit code and report

Before the final deadline of the project, as stated in Section 3 of this document, submit an archive with all the developed code and resources, and the report document.

IMPORTANT: the code archive and the report are submitted separately on the Fénix system.

### 2.8.1. Code archive requirements

- ZIP format - without compiled code, only source and build scripts;
- The mandatory file name is `CXX_WWW_HHMM_L_solution.zip`;
- README file, describing the required platform (e.g., Linux 64-bit, Ubuntu 20.04.3 LTS, Java 8u181) and setup instructions;
- All configuration files and scripts required to configure the solution on the specified platform;
- All developed source code;
- Existing tests and example files.

## 2.9. Check presentation session

The project presentations will occur on the dates following the submission deadline.  
The presentation session calendar will be made available during the final days of the project.

Each group is assigned to a session, in their respective campus, preferably in the time-slot of laboratory they are enrolled to.  
If your group requires a change in the proposed slot, please contact faculty in advance.

## 2.10. Present and defend

Each group will have to attend the full presentation session where they will present.  
The presentation slides must be in English and the presenters should also present in English.  
For the discussion questions, students can answer in Portuguese.

### 2.10.1. Presentation outline

The presentations will be organized as follows:

- 8 minutes for presentation of the work done, supported by slides, including a mandatory 2 minute live demo  
(also prepare a video of the demo, as backup, just in case there is a technical problem);
- 7 minutes for questions and answers.

It is highly recommended that each presentation includes:

- a slide with the general architecture;
- a slide with the key distribution and management mechanism, when appropriate;
- a slide with the developed protocol.

Each group member must participate and talk in the presentation, and be prepared to answer individual questions.  
If necessary, a more detailed discussion will be scheduled with each group.

### 2.10.2. Presence

The presentations are done by the whole group, in person, on campus.
Each group must attend from the beginning of their assigned session and remain for the duration of it.

### 2.10.3. Presentation archive requirements

IMPORTANT: after making the presentation, you will have to submit the presentation and video on Fénix.

- ZIP format;
- The mandatory file name is `CXX_WWW_HHMM_L_presentation.zip`;
- Presentation in PDF and also in source format (e.g. PowerPoint);
- Text file containing link(s) to download the demo video and screenshots of the solution.
The links must be valid for one month, at least.
The video can also be published in YouTube or a similar platform.

### 2.10.4 Grading

The project grade will take into account:

- Security design/rational (30%);
- Security implementation (30%);
- Report (20%);
- Presentation (20%).

# 3. Calendar

The relevant dates for the project are shown in the following calendar.

| **Stage**                  | **Deadline**                                                                      |
| ---------------------------|-----------------------------------------------------------------------------------|
| 1. Assemble team           | On the labs, before Friday, December 2nd, 2021 |
| 2. Pick topic              | Topic list published: Monday, December 6th<br />Form opens: Thursday, December 9th, 13:00<br />**Closes: Friday, December 10th, 17:00** |
| 3. Write proposal          | **Submit: Friday, December 17th, 17:00** |
| 4. Await approval          | Week of December 20th |
| 5. Develop project         | During the weeks of January 10th - 17th - 24th, 2022, articulated with other coursework |
| 6. Prepare demonstration   | Start preparing once you have the intermediate version of the work |
| 7. Write report            | Update as you complete basic, intermediate and advanced versions |
| 8. Submit code and report  | **Friday, January 28th, 17:00** |
| 9. Check presentation session | Opens: Wednesday, January 26th<br />**Changes close: Friday, January 28th, 18:00** |
| 10. Present and defend     | Sessions start Monday, January 31st |

----

## 3.1. Updates

IMPORTANT: keep track of the course [web site](https://fenix.tecnico.ulisboa.pt/disciplinas/SIRS/2021-2022/1-semestre) for updates and links to online forms.

If there are changes to this document, they can be consulted in the _Git Commit History_.

## 3.2. Final words

We wish you all the best in this technical venture!  
Make the most of it and ask for our feedback as much as possible.

----

[SIRS Faculty](mailto:meic-sirs@disciplinas.tecnico.ulisboa.pt)
