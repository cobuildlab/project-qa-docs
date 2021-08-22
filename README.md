# [Cobuild Lab's](https://cobuildlab.com) documentation for Project Management and Software Development Conventions

This is the main repositoty of documentation for the company. In here we set up all the agreements for the different processes of the Organization.

# 1. Project Management Process:

Process to follow for the Process of Project Management in Cobuild Lab. 

Cobuild Lab uses the Kanban agila framework for the Software Development Process.  For more information on the framework, please [READ THIS](https://www.atlassian.com/agile/kanban)

  ## 1.2. Terms Definition [Link](/conventions/terms.md)

  ## 1.3. Roles and Responsabilities [Link](/conventions/roles.md)

  ## 1.4. PRE project Activities

Here we outline the main activities when starting a project in a non-necessary sequential order:

### 1. Cerate the Project Slack Channel 

When a project is started the first step is to assemble the team in a slack dedicated project channel. Project Channel names start with a double hyphen “--”, followe by the short name of the project in lowercase. Example: “--awaken-flow”, “--c2g”

### 2. Create the Project Folder 

The Project folder must be created under the main “Projects” folder managed by the organization. (Google Drive).

Link to the main Project Folder: https://drive.google.com/drive/u/1/folders/1Uz91sEjNBETLiQJgy_kmx8HODPFMRaQd

Convention Link: [Project Folder Structure](/conventions/project-folder-structure.md)

**Note: Make sure you pin the link of the folder to the Project Slack Channel.**

### 3. Seupt Github 

- Create the code repositories under the [repositories naming convention](/conventions/repository-name.md)
- Set up the Kanban project with the [Kanban Project Conventions](/conventions/github-project-kanban.md). The Project Kanban is created in the main repository of the project, the WEB for web projects and the MOBILE for Mobile applications.
- Create a Github Team, and add all the participants to the Team. [See How](/how-tos/github-team-management.md)
 
### 4. Provisioning: 

One of the first task to do in a project is consult with the team or Technical Leader to create the first activities in the projects Kanban board to request the IT assets to be able to run the project without any problems. This assets usually include:

- 8base workspace
- Servers
- Databases
- Other hosting services
- Github CI/CD or team members
- Buddy CI/CD
- DNS Setup, etc

### 7. Subscribe Github notifications to Slack Channel

Using the GIthub bot installed in the Cobuild Lab Slack Workspace, subscribe all the repositories for the project to send notifications to the Project Slack Channel.

Reference: [https://slack.github.com/](https://slack.github.com/)

### 8. The full scope of the project must be shared with the Development Team to create an Execution Plan with milestones and deliverables.

The Project Management team: Project Manager and Product Manager or QA, must ensure that the full scope of the project is shared with the whole team for be revised, and a Planning meeting must be set to define dated Milestones for the project. 

### 9. Communicate Milestones in Github Project Kanban and Milestones Document

Once the requirements have been reviewed, and the Milestones have being agreed, the Project Manager must ensure that all members and stakeholders have access to the Milestones document by placing the document in the main Project Dashboard.

**PROJECT DASHBOARD:** [https://docs.google.com/spreadsheets/d/1RwSRlAVYLjrnWtUuE0AKxEwYcAH-Vtsn3f8g1-tizzI/edit#gid=0](https://docs.google.com/spreadsheets/d/1RwSRlAVYLjrnWtUuE0AKxEwYcAH-Vtsn3f8g1-tizzI/edit#gid=0)
**8base's PROJECT DASHBOARD:** [https://docs.google.com/spreadsheets/d/1G8ybAmRXWhPNDDYKhZXH5FPUZRB-59rS7Vd2lkLxYGw/edit#gid=0](https://docs.google.com/spreadsheets/d/1G8ybAmRXWhPNDDYKhZXH5FPUZRB-59rS7Vd2lkLxYGw/edit#gid=0)

### 10. Provide access to the team members to the Github repositiories, Project Folder and any other external assets (Invision, XD, Auth0, AWS, Buddy works, etc)

Ensure all team members have access to all the Project assets.

### 11. Set Fisherman (activity Tracking for developers) for the project’s repositories tracking and standups.

In https://app.fisherman.dev create the project and make sure you set:

- The Fisherman Project for this specific project
- The Standup bot for the Project
- Link the related Github repositories to the Fisherman Project
- Setup the emails configuration for sending emails to the Project Slack channel, and for creating Github Issues

**HOW TO:** [How to Configure Fisherman for a Project](/how-tos/setup-fisherman.md)
**Note: Make sure that you pin the Project Email address in the Project Slack Channel**

### 12. Set the meetings for the Planning and Daily Standups with the development team.

In coordination with the Development Team, setup the recurrent Daily meeting and any other required meeting.

### 13. Set the communication channels with the Customer.

Examples of communication channels:

- Slack channel in Cobuild Lab's Slack workspace
- Slack channel in 8base's Slack workspace
- Whatsapp group

### 14. Set the Client Feedback Spreadsheet

**TEMPLATE:** https://docs.google.com/spreadsheets/d/1QkpgUniCL1NhPObehKKKxsy-AOzFiMTKJtR8oEefrGA/edit#gid=0

### 15. Check Tickets integrity

Ticket specification is responsabilitye of the Project Manager, QA and Technical Lead.

- If the Issue is estimated to be longer than 2 days, it needs to be splitted.
- If the Issue doesn't have the specification completed, it needs to be completed.
- If the Issue doesn't have the technical specification completed, it needs to be completed.
- If the Issue requires a UI and it doesn't have it, it needs to be completed.

It is understood that all the requirements for a Project will not be ready before the start of the project, for this, the tickets need to be labeled with the proper "need". Example: `need-customer"` `need-desing` `need-techincal-specification`

  ## 1.5. IN project Activities (Software Development Process)
  
### 1. Daily Meeting

This is the meeting that needs to be celebrated everyday to sync the team, clarify the work in scope (the TODO column in the Kanban) and make sure that everybody understand the pending tickets.

This meeting is conducted by the Project Manager, and it requires the participation of all the team members.

### 2. Planning Meeting

When necessary, a longer meeting for clarifying requirements can be scheduled. The goal here is to provide more information on the work in scope (TODO column in the Kanban).

### 4. Code Reviews

The Technical leader assigned for the team must review every Pull Request to be in

### 5. Continuos testing and Quality Assurance:
### 6. Releases

The release management process comprehends the activities to move forward the source code and features from one environment to another one.

It is reponsability of the Project Manager to decide when is necessary to create a new release.

New releases are created from the integration environment (main) and moved forward through the different development environments (qa, stage, master).

The person who is reponsible to create the release is the **Product and QA Specialist**.

**HOW TO:**[How to Create a Release](/how-tos/create-a-release.md)

### 7. Client meetings
### 8. Stakeholders status communication
### 9. Client deliverables
### 10. Weekley internal status update




  ## 1.6. POST project Activities (Warranty and Support)

# 2. Software Development Conventions:

The complete list of conventions and agreements for codebases can be found in [here](https://github.com/cobuildlab/conventions)

# 3. TODO: 

1. Requirement Management: (documentacion de requerimientos, alcance del requerimiento, cambio de alcance).
1. Unit Testing, Check lists, Definition of Done
1. Project Management Strategy: https://docs.google.com/document/d/1AGbBEnYg5_k0Bd-e4j-TdmNk3qu4vdAYhExS9kD6C-Q/edit (Scrum + XP + Kanban)
1. Environments: https://docs.google.com/document/d/1AGbBEnYg5_k0Bd-e4j-TdmNk3qu4vdAYhExS9kD6C-Q/edit 
1. Release processes: Main -> QA, QA -> Stage, Stage -> Prod: https://docs.google.com/presentation/d/1hIx5LVp6RTd7bKj8ZSllu4aZX2gf_w5frNTMq2DGbG0/edit#slide=id.p
1. Quality Assurence: Testing Plan, Test Cases, Issues and Issues reporting
1. Miscelaneos
1. Test Automation
1. Coonstant Education and Training
1. TMMI
2. Template for User Stories
3. Template for CLIENT FEEDBACK (Issue tracking)
4. Release process por environments
5. Roles and responsabilities for Project Management and coordination: https://docs.google.com/document/d/1AGbBEnYg5_k0Bd-e4j-TdmNk3qu4vdAYhExS9kD6C-Q/edit
6. Name releases (versioning): https://semver.org/
7. Emails content for releases to clients
8. Form to incoming request for features / issues / bugs / enhancements / etc
9. TODO list for Env Release
10. TEMPLATE: Follow up emails
11. Client Feedback Spreadsheet:
12. Business Rules Document
13. Create release for the QA
14. Template for closing project
15. testimonials
16. Change Control Forms
17. Dress coode and conditions for Client Presentations: https://www.thecouchmanager.com/5-video-call-setup-tips/
18. EMAIL TEMPLPATE for Meeting Agenda
19. Email TEMPlATE and proocudere for Prooduction Releases
20. Client Feedback Spreadsheet: Change control and Client Feedback





  
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjA3ODY4OTMyNywxOTM0MzAxNDI2LDIwOT
Q0MTUyMzQsLTUyODczNjkwMSwxMjEzNjIyMDEwLDE2MDY1MDc1
MzFdfQ==
-->