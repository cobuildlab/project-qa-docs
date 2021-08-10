# [Cobuild Lab's](https://cobuildlab.com) documentation for Project Management and Software Development Conventions

This is the main repositoty of documentation for the company. In here we set up all the agreements for the different processes of the Organization.

# 1. Project Management:

Process to follow for the Process of Project Management in Cobuild Lab.

  ## 1.2. Terms Definition [Link](/terms.md)

  ## 1.3. Roles and Responsabilities [Link](/roles.md)

  ## 1.4. PRE project Activities

Here we outline the main activities when starting a project in a non-necessary sequential order:

### 1. CREATE THE PROJECT SLACK CHANNEL: 

When a project is started the first step is to assemble the team in a slack dedicated project channel. Project Channel names start with a double hyphen “--”, followe by the short name of the project in lowercase. Example: “--awaken-flow”, “--c2g”

### 2. CREATE THE PROJECT FOLDER: 

The Project folder must be created under the main “Projects” folder managed by the organization. (Google Drive)

### 3. SET UP GITHUB: 

- Create the code repositories under the [repositories naming convention](/conventions/repository-name.md)
- Set up the Kanban project with the [Kanban Project Conventions](/conventions/github-project-kanban.md)
- Create a Github Team, and add all the participants to the Team. [See How](/how-tos/github-team-management.md)
 
### 4. PROVISIONING: 

Infrastructure Provisioning: Servers, 8base workspace, hosting, GitHub, slack channel, buddy works, DNS setup, etc

### 6. Set Github Kanban with columns and labels
### 7. Subscribe Github notifications to Slack Channel
### 8. The full scope of the project must be shared with the Development Team to create an Execution Plan with milestones and deliverables.
### 9. Create Milestones in Github Project Kanban
### 10. Provide access to the team members to the Github repositiories, Project Folder and any other external assets (Invision, XD, Auth0, AWS, Buddy works, etc)
### 11. Set Fisherman (activity Tracking for developers) for the project’s repositories tracking and standups.
### 12. Complete all User Stories (Issues or Tickets) in the project scope on a Planning meeting.
### 13. Set the meetings for the Planning and Daily Standups with the development team.
### 14. Set the communication channels with the Customer.
### 15. Kickoff meeting with the Development Team.
### 16. Ensure that all requirements for the full development of the project are in place or scheduled to be in place. 
### 17. High level Data model 

  ## 1.5. IN project Activities (Software Development Process)
  
### 1. DAILY MEETING:
### 2. PLANNING MEETING:
### 4. CODE REVIEW and INTEGRATION:
### 5. TESTING AND QUALITY ASSURANCE:
### 6. RELEASE MANAGEMENT:

The release management process comprehends the activities to move forward the source code and features from one environment to another one.

It is reponsability of the Project Manager to decide when is necessary to create a new release.

New releases are created from the integration environment (main) and moved forward through the different development environments (qa, stage, master).

The person who is reponsible to create the release is the **Product and QA Specialist**.

[How to Create a Release](/how-tos/create-a-release.md)


### 7. TICKET QUALITY TEST:

Ticket specification is responsabilitye of the Project Manager, QA and Technical Lead.

- If the Issue is estimated to be longer than 2 days, it needs to be split.
- If the Issue doesn't have the specification completed, it needs to be completed.
- If the Issue doesn't have the technical specification completed, it needs to be completed.
- If the Issue requires a UI and it doesn't have it 





  ## 1.6. POST project Activities (Warranty and Support)

# 2. Software Development Conventions:

The complete list of conventions and agreements for codebases can be found in [here](https://github.com/cobuildlab/conventions)

# 3. TODO: 

1. Requirement Management: (documentacion de requerimientos, alcance del requerimiento, cambio de alcance).
1. Coding Conventions: https://github.com/cobuildlab/conventions
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






  
