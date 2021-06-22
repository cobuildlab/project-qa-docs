# Conventions for naming code repositories

At (Cobuild Lab)[https://cobuildlab.com] we lean in the repository pattern of (multi-repo)[https://www.hashicorp.com/blog/terraform-mono-repo-vs-multi-repo-the-great-debate]. 

With this in mind we separate every component in the architecture of a system in it's own code repository, and we use the following rules to name them:

1) For convinience we name all the repositories using as prefix the name of the prokect
2) Following the prefix we indicate the architectural type of the component that is gonna live in the repository:
    - `web` for web applications
    - `admin` for backoffices or admin applications
    - `functions` for cloud functions repositories
    - `api` for full api components
    - `mobile` for mobile applications
    - `shared` for a library of shared resources
    - `landing` for web landings
    - `utils` for helpers and tools
3) OPTIONAL, if multuple components use the same type, we include a descriptive word before the `type`
4) We use only lowercase and separate the words with hypens `-` 

Example:

Let's assume that we have a project with the shortname of `jenkins` that has all the components mentioned above, including 3 different `api` components and 2 different `web` components, then we have:

`jenkins-members-web`
`jenkins-users-web`
`jenkins-auth-api`
`jenkins-tokens-api`
`jenkins-admin`
`jenkins-functions`
`jenkins-mobile`
`jenkins-shared`
`jenkins-landing`
`jenkins-utils`
