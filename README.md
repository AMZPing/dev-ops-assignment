# dev-ops-assignment

The goal of the assignment is to build a pipeline to automatically create a test environment everytime a new pull request is opened and shutdown the environment every time one is closed. If the PR is updated the environment should be updated as well. 

Keep it simple, there are many ways to approach this problem and simplicity and security are the top priority.

Required Tools
-------

* CI: Github Actions **OR** AWS CodeBuild
* Image Repository: Github Packages **OR** AWS ECR
* Deployment: AWS ECS **OR** docker-swarm running on ECS 
* Infrastructure Automation: terraform

You may also use **lambda** as needed in your infrastructure automation, but it must be defined and deployed via terraform. 

There should be absolutely no manual configuration required beyond provisioning initial access to the aws account.

This project will be performed in two phases.

* Design Phase - We will iterate on your approach via chat until we arrive on a mutually accepted solution.
* Implementation Phase - Once designed you will be required to implement the solution.
  1. You will work directly in the repository
  2. Create a terraform root folder where all your work will go
  3. Develop your solution
  4. You can commit directly to the main branch
* Review Phase - we will review your submission in two steps
  1. Record a video explaining what you built and how it works, make sure to include an example of creating a new PR and having the new environment spin up.
  2. Once we've reviewed the video from step 1 we will schedule a call to review it in detail and ask questions about the solution.

 **You are welcome to ask questions during any point of the project, how you approach the communication and time/expectation management just as important as the code you write**


It should be trivial to do this in AWS Free Tier.
