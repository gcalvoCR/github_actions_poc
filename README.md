# github_actions_poc

# CI/CD

CI/CD is a method to frequently deliver apps to customers by introducing automation into the stages of app development. The main concepts attributed to CI/CD are continuous integration, continuous delivery, and continuous deployment. CI/CD is a solution to the problems integrating new code can cause for development and operations teams (**AKA "integration hell"**).

![CI-CD-Pipeline](./ci-cd-flow.png)
# What is continuous integration?

The "CI" in CI/CD always refers to continuous integration, which is an automation process for developers.

The solution to the problem of having too many branches of an app in development at once that might conflict with each other.

# What is continuous deployment?
The "CD" in CI/CD refers to continuous delivery and/or continuous deployment, which are related concepts that sometimes get used interchangeably. Both are about automating further stages of the pipeline, but they’re sometimes used separately to illustrate just how much automation is happening.


# Advantages of CI/CD

- Fault isolation is simpler and faster. Since changes are smaller, it is easier to isolate the changes that cause a bug after deployment. This makes it easier to fix or roll back changes if necessary
- Since CI/CD encourages small, frequent changes, code review time is shorter
- A major part of the CI/CD pipeline is the automated testing of critical flows for a project. This makes it easier to prevent changes that may break these flows in production
- Better code quality is ensured because you can configure the pipeline to test against linting rules

# Github Actions


### Reference 
https://blog.logrocket.com/ci-cd-node-js-github-actions/
