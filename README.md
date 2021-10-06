# [Cobuild Lab's](https://cobuildlab.com) documentation for Project Management and Software Development Conventions

This is the main repository of documentation for the company. In here we set up all the agreements for the different processes of the Organization.

# 1. Project Management Process:

Information to follow for the Process of Project Management in Cobuild Lab:

### Core Values:

1.  Distributed remote teams
2.  Customer-centric development process
3.  Engineering first approach to solve problems
4.  Fast delivery over technical proficiency 
5.  Extremely Agile
6. Sustainable Software and Zero Waste: Fast and small continuous delivery + Early retrospective

### Framework:

Cobuild Lab uses the Kanban agile framework for the Software Development Process.  For more information on the framework, please [READ THIS](https://www.atlassian.com/agile/kanban)

### Preferred Tooling:

1. Typescript and Python
2. ReactJs and React Native
3. 8base and AWS
4. GitHub, Buddy Works, and Slack
5. ESLINT and Husky

### Project Management Keys

1. Real-time communication and high availability is necessary
2. Produce high-quality software to the customer in the shortest amount of time
3. Communication must be transparent between customer and development team
4. Automated unit testing and functional testing
5. Planned activities can change at any time
6. Only work in top priority items
7. All the tasks, requirements, and issues of the projects are visible all the time in the Kanban Board.
8. Automated Deployment
9. Sprints of 1 or 2 weeks tops.

## 1.2. Terms Definition [Link](/conventions/terms.md)

## 1.3. Roles and Responsibilities [Link](/conventions/roles.md)

## 1.4. PRE project Activities

Here we outline the main activities when starting a project in a non-necessary sequential order:

### 1. Create the Project Slack Channel 

When a project is started the first step is to assemble the team in a slack dedicated project channel. Project Channel names start with a double hyphen “--”, followed by the short name of the project in lowercase. Example: “--awaken-flow”, “--c2g”

### 2. Create the Project Folder 

The Project folder must be created under the main “Projects” folder managed by the organization. (Google Drive).

Link to the main Project Folder: https://drive.google.com/drive/u/1/folders/1Uz91sEjNBETLiQJgy_kmx8HODPFMRaQd

Convention Link: [Project Folder Structure](/conventions/project-folder-structure.md)

**Note: Make sure you pin the link of the folder to the Project Slack Channel.**

### 3. Setup GitHub 

- Create the code repositories under the [repositories naming convention](/conventions/repository-name.md)
- Set up the Kanban project with the [Kanban Project Conventions](/conventions/github-project-kanban.md). The Project Kanban is created in the main repository of the project, the WEB for web projects and the MOBILE for Mobile applications.
- Create a GitHub Team, and add all the participants to the Team. [See How](/how-tos/github-team-management.md)
 
### 4. Provisioning: 

One of the first task to do in a project is consult with the team or Technical Leader to create the first activities in the projects Kanban board to request the IT assets to be able to run the project without any problems. These assets usually include:

- 8base workspace
- Servers
- Databases
- Other hosting services
- GitHub CI/CD or team members
- Buddy CI/CD
- DNS Setup, etc

### 7. Subscribe GitHub notifications to Slack Channel

Using the GitHub bot installed in the Cobuild Lab Slack Workspace, subscribe all the repositories for the project to send notifications to the Project Slack Channel.

Reference: [https://slack.github.com/](https://slack.github.com/)

### 8. The full scope of the project must be shared with the Development Team to create an Execution Plan with milestones and deliverables.

The Project Management team: Project Manager and Product Manager or QA, must ensure that the full scope of the project is shared with the whole team for be revised, and a Planning meeting must be set to define dated Milestones for the project. 

### 9. Communicate Milestones in GitHub Project Kanban and Milestones Document

Once the requirements have been reviewed, and the Milestones have being agreed, the Project Manager must ensure that all members and stakeholders have access to the Milestones document by placing the document in the main Project Dashboard.

**PROJECT DASHBOARD:** [https://docs.google.com/spreadsheets/d/1RwSRlAVYLjrnWtUuE0AKxEwYcAH-Vtsn3f8g1-tizzI/edit#gid=0](https://docs.google.com/spreadsheets/d/1RwSRlAVYLjrnWtUuE0AKxEwYcAH-Vtsn3f8g1-tizzI/edit#gid=0)
**8base's PROJECT DASHBOARD:** [https://docs.google.com/spreadsheets/d/1G8ybAmRXWhPNDDYKhZXH5FPUZRB-59rS7Vd2lkLxYGw/edit#gid=0](https://docs.google.com/spreadsheets/d/1G8ybAmRXWhPNDDYKhZXH5FPUZRB-59rS7Vd2lkLxYGw/edit#gid=0)

### 10. Provide access to the team members to the GitHub repositories, Project Folder and any other external assets (Invision, XD, Auth0, AWS, Buddy works, etc)

Ensure all team members have access to all the Project assets.

### 11. Set Fisherman (activity Tracking for developers) for the project’s repositories tracking and standups.

In https://app.fisherman.dev create the project and make sure you set:

- The Fisherman Project for this specific project
- The Standup bot for the Project
- Link the related GitHub repositories to the Fisherman Project
- Set up the emails configuration for sending emails to the Project Slack channel, and for creating Github Issues

**HOW TO:** [How to Configure Fisherman for a Project](/how-tos/setup-fisherman.md)
**Note: Make sure that you pin the Project Email address in the Project Slack Channel**

### 12. Meetings: Set the meetings for the Planning and Daily Standups with the development team and follow-up meeting with the Client.

In coordination with the Development Team, setup the recurrent Daily meeting and any other required meeting.

In coordination with the Client and other project stakeholders, setup a recurrent bi-weekly meeting to update the client with the project status, and provide deliverables of the Product.

### 13. Set the communication channels with the Customer.

Examples of communication channels:

- Slack channel in Cobuild Lab's Slack workspace
- Slack channel in 8base's Slack workspace
- Whatsapp group

### 14. Set the Client Feedback Spreadsheet

In order to make easy the way the client provides his feedback, the project manager will do a form with the following questions:
- Platform / App Version (required)
- Task Name (required) (max character count 75)
- Additional Details (Optional)
- Related Images/Videos/Files
- Assigned to: Cobuild team or Pending from the client (Required)

**TEMPLATE:** https://docs.google.com/forms/d/1WAReS3xHJPPZl0ipONBN8sEGY2bbm50Rs_OjggGh5d8/edit?usp=sharing

In order to do the follow up, the form resposes will be saved in the spreedsheet where the project manager will add the following fields:
- Status: In Progress, Done, Backlogged or Icebox

**TEMPLATE:** https://docs.google.com/spreadsheets/d/1SujYa381gjWRN2P4aAjJclURp7b_A6L3mypdWCnnPlk/edit?usp=sharing

In every project update (meeting or email) the client should be updated of the status of the tasks that he created and when it will be done.

### 15. Check Tickets integrity

Ticket specification is responsibility of the Project Manager, QA and Technical Lead.

- If the Issue is estimated to be longer than 2 days, it needs to be split.
- If the Issue doesn't have the specification completed, it needs to be completed.
- If the Issue doesn't have the technical specification completed, it needs to be completed.
- If the Issue requires a UI and it doesn't have it, it needs to be completed.

It is understood that all the requirements for a Project will not be ready before the start of the project, for this, the tickets need to be labeled with the proper "need". Example: `need-customer"` `need-desing` `need-techincal-specification`

  ## 1.5. IN project Activities (Software Development Process)
  
### 1. Daily Meeting

This is the meeting that needs to be celebrated every day to sync the team, clarify the work in scope (the TODO column in the Kanban) and make sure that everybody understand the pending tickets.

This meeting is conducted by the Project Manager, and it requires the participation of all the team members.

### 2. Planning Meeting

When necessary, a longer meeting for clarifying requirements can be scheduled. The goal here is to provide more information on the work in scope (TODO column in the Kanban).

### 4. Code Reviews

The Technical leader assigned for the team must review every Pull Request to be incorporated to the code respositories to be integrated in the development environments. Likewise, every Pull Request needs to be approved for at least the Technical Leader of the team.

### 5. Continuous testing and Quality Assurance

Is Cobuild Lab's philosophy that Testing and QA has to be a continuos process. Is the responsability of the Project Manager, in conjunction with the team to coordinate a batch of ready tickets to be delivered to the QA or STAGE environments at any point during the week.

As part of the Testing and Quality Assurrance process the QA specialist needs to list the Test cases for testing the system. For this, a template is provided: https://docs.google.com/spreadsheets/d/1V1gJDRWETi8lEWzYVWM9_5ASFzVoQrcUZMeqcSLVaO0/edit#gid=0

### 6. Releases

The release management process comprehends the activities to move forward the source code and features from one environment to another one.

It is responsibility of the Project Manager to decide when is necessary to create a new release.

New releases are created from the integration environment (main) and moved forward through the different development environments (qa, stage, master).

The person who is responsible to create the release is the **Product and QA Specialist**.

**HOW TO:** [How to Create a Release](/how-tos/create-a-release.md)

### 7. Client meetings

Normally, the Project Manager, needs to celebrate bi-weekly meetings with the client to provide status of the Project and Client Feedback open items, and also to present deliverables.

**Note:** Dress coode and conditions for Client Presentations: https://www.thecouchmanager.com/5-video-call-setup-tips/

### 8. Stakeholders status communication

Once a week, on Mondays, the Project Manager needs to update the Project Dashboard spreadsheet to maintain every project stakeholder with an up to date status.

  ## 1.6. POST project Activities (Delivery and Warranty)

### 1. Closing Email communication

At the end of the development of each project, we need to communicate the Client the milestone:

TEMPLATE: [Project Final Delivery](/templates/project-final-delivery.md)


# 2. Software Development Conventions:

The complete list of conventions and agreements for code bases can be found in [here](https://github.com/cobuildlab/conventions)
