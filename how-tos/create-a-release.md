# How to Create a Release using Github

A release is a Pull Request created from on development environment to another one indicating which features or bug fixes are moved from one place to another. 

The first thing to decide is the version of the release:

- If is a new release, this is a release started from the integration environment (main) to the testing environment (qa) then a new version needs to be created.
- If is a release from the testing environment (qa) and forward, we should use the same release used to intially move the features and fixes from `main` to `qa`
- The convention for naming the version is https://semver.org/ Example: 1.1.0, 2.0.0, 3.0.1
- In general, use one of this 3 rules:
    * Increase the first number if the release brings new major features or changes, set the second and the third number to 0
    * Increase the second number if only new small or minor features are added to existing features, keep the first number as it was before and set the third number to 0
    * Increate the third number if the release only contains bug fixes, keep the first and the second number as they were in the previous release.
- Create the Pull Request associated with the release an include in the description all the tickets that are included in the Release
- If there are multiple components that involve code changes with the features included in the release, all the Pull Requests should have the same name
- The description of the Pull Request must contain the Name and links of the Github Issues associated with the release.

Release (Pull Requests) are named using the following convention:

`RELEASE <version> TO <ENVIRONMENT NAME>`

Examples:

`RELEASE 1.2.1 TO QA`
`RELEASE 1.2.1 TO STAGE`
`RELEASE 1.2.1 TO MASTER`


## Steps to create a Relase Pull Request:

1. Navigate to the repository where the Release should be created
2. Click in the Pull Request tab of the repository
3. Click NEW
4. Specify the name and description of the Release Pull Request
5. Assign a reviewer, this is normally the job of the Technical Leader for the project

