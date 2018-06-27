# Workflows

## Agile Software Development

- Scrum
- Kanban

## Testing, Integration, Deployment, Delivery

- [Continuous Integration/Continuous Delivery](https://www.atlassian.com/continuous-delivery/ci-vs-ci-vs-cd)
  - To put it simply continuous integration is part of both continuous delivery and continuous deployment. And continuous deployment is like continuous delivery, except that releases happen automatically.
  - CI
    - Developers practicing continuous integration merge their changes back to the main branch as often as possible. The developer's changes are validated by creating a build and running automated tests against the build. By doing so, you avoid the integration hell that usually happens when people wait for release day to merge their changes into the release branch.
    - Continuous integration puts a great emphasis on testing automation to check that the application is not broken whenever new commits are integrated into the main branch.
  - CD
    - Delivery: [Continuous delivery](https://www.atlassian.com/continuous-delivery) is an extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button.
      - In theory, with continuous delivery, you can decide to release daily, weekly, fortnightly, or whatever suits your business requirements. However, if you truly want to get the benefits of continuous delivery, you should deploy to production as early as possible to make sure that you release small batches, that are easy to troubleshoot in case of a problem.
    - Deployment: Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes all stages of your production pipeline is released to your customers. There's no human intervention, and only a failed test will prevent a new change to be deployed to production.
      - Continuous deployment is an excellent way to accelerate the feedback loop with your customers and take pressure off the team as there isn't a *Release Day* anymore. Developers can focus on building software, and they see their work go live minutes after they've finished working on it.

## [CI/CD Tools](https://blog.takipi.com/jenkins-vs-travis-ci-vs-circle-ci-vs-teamcity-vs-codeship-vs-gitlab-ci-vs-bamboo/)

- Jenkins
  - Most well-known
  - Free and open-source
- Travis CI
  - More CI than CD
  - Free for open-source
- TeamCity
  - Made by JetBrains
  - Free professional license (100 build configs, full features)
- CircleCI
  - Good on VC (GitHub/Bitbucket etc.)
  - Auto-cancel redundant builds on GitHub
- Codeship
  - Pro version uses Docker
  - Free plan (100 builts per month for unlimited projects/users/teams)
  - [Public collection of utilities](https://github.com/codeship-library)
- GitLab CI
  - Free with GitLab (Community Edition)
  - Open-source
- Bamboo
  - Made by Atlassian
    - Good integrations with their other products (e.g. JIRA/Bitbucket)
  - Pay per "agent," no free plan