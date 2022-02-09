# Convention for Kanban board in Github Projects

## REF:

- [Roles](https://github.com/cobuildlab/project-qa-docs/blob/main/conventions/roles.md)

## VALUES:

- Reduce the number of columns to minize the work of moving tickets around/
- Visually communicate the status of the project and each column.

## INTRODUCTION

In order to properly manage the columns or stages in the project Kanban, a convention has been developed. 

The convention is centered around the IN PROGRESS stage or column, where all the columns from the left are planning columns, representing priority to be developed, and all the columns from the right are environment columns where the features and bug fixes move forward. 

## COLUMNS:

From left to right:

🥶 ICEBOX: 
Maintainer: Project Manager, Technical Leader, QA Specialist 
Description: Tasks on hold, nice to haves, or are currently out of scope.

2️⃣ BACKLOG:
Maintainer: Project Manager, Technical Leader
Description: Tasks in scope, but that are not yet defined or scheduled. Tasks in project scope that have already been fully described and tagged in a milestone and are ready to be moved to TODO (planned to be executed).

1️⃣ TODO:
Maintainer: Project Manager, Technical Leader, Developers
Description: Tasks expected to be completed in the current sprint, iteration or week. New Bugs are created here. **Items on this column should be sorte in the order that is desired to be executed: Top items first**

🟩 IN PROGRESS:
Maintainer: Developer
Description: Tasks actively being developed

🛑 CODE REVIEW
Maintainer: Tasks associated to Pull Request waiting to be merged

⏯ DONE | MAIN:
Maintainer: Developer
Description: First Integration environment. Code approved and Integrated features and bug fixes live here first. 

⏩ DONE | [QA, STAGE] (Optional per project)
Maintainer: Product Specialist
Description: Other more stable environments that hold features and bug fixes before PROD environments

☑️ DONE | MASTER | PROD 
Maintainer: Product Specialist
Description: Completed closed tasks and Pull Requests that are delivered to the Production userss

Example:


| 🥶 ICEBOX   | 2️⃣ BACKLOG  | 1️⃣ TODO  | 🟩 IN PROGRESS  | 🛑 CODE REVIEW  | ⏯ DONE - MAIN  | ⏩ DONE - QA  | ⏩ DONE - STAGE  |  ☑️ DONE - MASTER - PROD  |
|---|---|---|---|---|---|---|---|---|
|   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |
|   |   |   |   |   |   |   |   |   |


## LABELS:

Normally columns are not enough to fully communicate the status of an Issue (Feature or Bug), sometimes it requires additional important information that we manage with labels:

-  🟨 `HIGHT-PRIORITY`: For marking Issues important above all
-  🟩 `qa-reviewed`:  For issues already reviewed by a QA 
-  🟥 `bug` or `bug-<Environment Name>`: A bug or problem in one of the environments


-  `need-customer` : Issues that are stopped or blocked by the Customer.
-  `need-design` : For issues that require or are missing the UI Designs
-  `need-documentation`: For Issues that need to be documented in the Business Rules document
-  `need-tech-spec`: For Issues that need technical assitant or require a Technical specification
-  `need-info`: Issues that need more information, and that information is not covered by the other labels.
  
-  `customer-support**: For issues related to users’ problems.

-  `api`: Label to indicate that an Issue corresponds to the backend of the project.
-  `mobile`: Label to indicate that an Issue corresponds to the Mobile part of the project.
-  `web`: Label to indicate that an Issue corresponds to the Web part of the project.
-  `website`: Label to indicate that an Issue corresponds to the Website part of the project.
  
  - `feedback-<>`: `DOCUMENTATION PENDING`


