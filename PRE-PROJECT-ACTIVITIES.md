
Here we outline the main activities when starting a project in a non-necessary sequential order:

### 1. Create the Project Slack Channel 

When a project is started the first step is to assemble the team in a slack dedicated project channel. Project Channel names start with a double hyphen “--”, followed by the short name of the project in lowercase. Example: “--awaken-flow”, “--c2g”

### 2. Create the Project Folder 

The Project folder must be created under the main “Projects” folder managed by the organization. (Google Drive).

Link to the main Project Folder: https://drive.google.com/drive/u/1/folders/1Uz91sEjNBETLiQJgy_kmx8HODPFMRaQd

Convention Link: [Project Folder Structure](/conventions/project-folder-structure.md)

**Note: Make sure you pin the link of the folder to the Project Slack Channel.**

### 3. Setup GitHub Repositories and Team

- Create the code repositories under the [repositories naming convention](/conventions/repository-name.md)
- Set up the Kanban project with the [Kanban Project Conventions](/conventions/project-kanban.md). The Project Kanban is created in the main repository of the project, the WEB for web projects and the MOBILE for Mobile applications.
- Create a GitHub Team, and add all the participants to the Team. [See How](/how-tos/github-team-management.md)
 
### 4. Provisioning Infrastructure: 

One of the first task to do in a project is consult with the team or Technical Leader to create the first activities in the projects Kanban board to request the IT assets to be able to run the project without any problems. These assets usually include:

- 8base workspace
- Servers
- Databases
- Other hosting services
- GitHub CI/CD or team members
- Buddy CI/CD
- DNS Setup, etc

### 5. Subscribe GitHub notifications to Slack Channel

Using the GitHub bot installed in the Cobuild Lab Slack Workspace, subscribe all the repositories for the project to send notifications to the Project Slack Channel.

Reference: [https://slack.github.com/](https://slack.github.com/)

### 6. Project Scope and Initial Documentation

The full scope of the project must be shared with the Development Team to create an Execution Plan with milestones and plan deliverables.

**VALUES:**

- Lean Documentation
- Deep Documentation on Demand
- If we are gonna have documentation, it needs to be well organized, using the agreed tools and easy to index
- Flexible Dates / Fixed Milestones

**TO START THE PROJECT, WE NEED a MINIMAL VERSION TO SATISFY:**

#### 6.1 Modules Diagram:

We need a Visual representation of the different logical parts of the system, and how they are organized and linked to each other.

[Example](./examples/modules-diagram.md)

#### 6.2 Project Plan on a Kanban Board:

We need to set all the Features on the Kanban board, organized by Modules, Status and Milestones.
 
The Kanban needs to provide enough information to answer the following:
 - What's the status of each Feature
 - What's completed
 - What's not on Scope
 - The next delivery date and what does that next delivery contains

#### 6.3 User Roles or Permissions

 We need a document that specifies what can and cannot do each role on the platform in each module and submodule:
 
[Template](https://docs.google.com/spreadsheets/d/1oEPdJdY3wpARI9qGikR56i0kUbFVLwUFAhSL0IRJo54/edit#gid=0)
 
#### Navigation Diagram

We need a document that indicates the navigation strategy on the Web or Mobile App. This document needs to answer:

- We must have all the possible screen on the system, including modal windows and dialogs
- Per screen, indicate which role can access the screen
- Must have a hirarchical structure to represent the main levels or navigation (Primary navigation)

[Example](./navigation-diagram.md)

#### User Stories
#### Initial Datamodel
#### Business Rules
#### UI and Screens
#### INTRO VIDEO


The Project Management team: Project Manager and Product Manager or QA, must ensure that the full scope of the project is shared with the whole team for be revised, and a Planning meeting must be set to define dated Milestones for the project. 


### 7. Communicate Milestones in GitHub Project Kanban and Milestones Document

Once the requirements have been reviewed, and the Milestones have being agreed, the Project Manager must ensure that all members and stakeholders have access to the Milestones document by placing the document in the main Project Dashboard.

**PROJECT DASHBOARD:** [https://docs.google.com/spreadsheets/d/1RwSRlAVYLjrnWtUuE0AKxEwYcAH-Vtsn3f8g1-tizzI/edit#gid=0](https://docs.google.com/spreadsheets/d/1RwSRlAVYLjrnWtUuE0AKxEwYcAH-Vtsn3f8g1-tizzI/edit#gid=0)
**8base's PROJECT DASHBOARD:** [https://docs.google.com/spreadsheets/d/1G8ybAmRXWhPNDDYKhZXH5FPUZRB-59rS7Vd2lkLxYGw/edit#gid=0](https://docs.google.com/spreadsheets/d/1G8ybAmRXWhPNDDYKhZXH5FPUZRB-59rS7Vd2lkLxYGw/edit#gid=0)

### 8. Provide access to the team members to the GitHub repositories, Project Folder and any other external assets (Invision, XD, Auth0, AWS, Buddy works, etc)

Ensure all team members have access to all the Project assets.

### 9. Set Fisherman (activity Tracking for developers) for the project’s repositories tracking and standups.

In https://app.fisherman.dev create the project and make sure you set:

- The Fisherman Project for this specific project
- The Standup bot for the Project
- Link the related GitHub repositories to the Fisherman Project
- Set up the emails configuration for sending emails to the Project Slack channel, and for creating Github Issues

**HOW TO:** [How to Configure Fisherman for a Project](/how-tos/setup-fisherman.md)
**Note: Make sure that you pin the Project Email address in the Project Slack Channel**

### 10. Meetings: Set the meetings for the Planning and Daily Standups with the development team and follow-up meeting with the Client.

In coordination with the Development Team, setup the recurrent Daily meeting and any other required meeting.

In coordination with the Client and other project stakeholders, setup a recurrent bi-weekly meeting to update the client with the project status, and provide deliverables of the Product.

### 11. Set the communication channels with the Customer.

Examples of communication channels:

- Slack channel in Cobuild Lab's Slack workspace
- Slack channel in 8base's Slack workspace
- Whatsapp group

### 12. Set the Client Feedback Spreadsheet

**TEMPLATE:** https://docs.google.com/spreadsheets/d/1QkpgUniCL1NhPObehKKKxsy-AOzFiMTKJtR8oEefrGA/edit#gid=0

### 13. Check Tickets integrity

Ticket specification is responsibility of the Project Manager, QA and Technical Lead.

- If the Issue is estimated to be longer than 2 days, it needs to be split.
- If the Issue doesn't have the specification completed, it needs to be completed.
- If the Issue doesn't have the technical specification completed, it needs to be completed.
- If the Issue requires a UI and it doesn't have it, it needs to be completed.

It is understood that all the requirements for a Project will not be ready before the start of the project, for this, the tickets need to be labeled with the proper "need". Example: `need-customer"` `need-desing` `need-techincal-specification`

