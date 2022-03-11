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

### Project Management Keys

1. Real-time communication and high availability is necessary
2. Produce high-quality software to the customer in the shortest amount of time
3. Communication must be transparent between customer and development team
4. Automated unit testing and functional testing
5. Planned activities can change at any time
6. Only work in top priority items
7. All the tasks, requirements, and issues of the projects are visible all the time in the [Kanban Board](/conventions/project-kanban.md).
8. Automated Deployment
9. Sprints of 1 or 2 weeks tops.

## 1.2. Terms Definition [Link](/conventions/terms.md)

## 1.3. Roles and Responsibilities [Link](/conventions/roles.md)

## 1.4. PRE project Activities [Link](/PRE-PROJECT-ACTIVITIES.md)

## 1.5. IN project Activities (Software Development Process)

### 0. Project Complexity

Is a subjective measure to communicate how complex is the project on development, testing, and requirements activities.

- This information will be recorded on the SIZE column of the **PROJECT MASTER SHEET**
- Possible values could be, in increasing order of complexity: **0,1,2,3,5,8**
- For determining the value of a project, members of the project can vote using the numerical values and use the Average or Median
- This value is relevant for measuring the amount of work that the team members are handling, and the relative speed given an specific amount of developers
- Is responsability of the **PROJECT MANAGER** to keep these numbers up to date for the **WEEKLY SCRUM COUNCIL**

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
