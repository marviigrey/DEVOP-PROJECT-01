###This is a devops project.

1. First step is creating a repository and setting up the repository according to the 
devops best practices.

2. Speaking of best practice,first approach isto Enable branch protection by setting up a different branch for checking our codes,more like a feature branch where the codes will be checked before pushing to the main branch by the help of pull request. This is already applied to this repository because there are two branches involved which are the main and feature branch.
3. The next step is to check for the code sent by the developers and dockerize them, we will build them privately and test them before pushing to the main branch,we do this the  same way we have handled this repo.
4. The next configuration is to set up your kubernetes cluster ready for deployment,this is where our containerized app will be hosted. we wil use AWS EKS managed cluster to deploy the application.


