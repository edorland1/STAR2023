### Introduction

GitHub Actions allows for the automation of tasks within your software development life cycle. Through GitHub actions users can automatically run their software testing scripts. 

### Key Vocabulary

#### Workflows
Workflows can be used to design, test, package, release, or deploy a project on GitHub. A workflow can be added to a repository in GitHub using the file name .github/workflows. Workflows consist of one or more jobs that are scheduled/triggered by an event. 

#### Events
Events are the activities that trigger the start of a workflow. Workflows can be triggered using pus or pull requests. 

#### Runners
Runners can be hosted by GitHub or own on your own and is basically considered as a server that has GitHub Actions runner application installed. A runner runs one job at a time and reports the progress to GitHub. 

#### Jobs
A job is a sequence of instructions that run on the same runner. A workflow containing multiple jobs will perform them in parallel by default. You may also set up a pipeline to conduct jobs in a specific order. 

#### Steps
A step is a single task that can be used to execute commands in a job. An action or a shell command can be used as a step. Each step of a task runs on the same runner, allowing all of the activities in that job to exchange data.

#### Actions
Actions are commands that are used to join steps to create a job. Actions can be created or found on the GitHub community. 

> ![alt text](https://docs.github.com/assets/images/help/images/overview-actions-design.png)  
> **Figure credit**: [GitHub Docs](https://docs.github.com/en/actions/learn-github-actions/introduction-to-github-actions) The components of GitHub Actions that work together to run jobs
