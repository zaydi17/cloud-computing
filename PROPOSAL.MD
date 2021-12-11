# Implement your own CD pipeline
In our project we want to implement a CD pipeline with Jenkins X. 
## Jenkins X
![concept image](https://jenkins-x.io/images/jx-arch.png)

Jenkins X uses 7 key capatilities
1. version control for all artifacts
2. automated deployment process
3. trunk-based development
4. continous integration
5. continous delivery
6. loosley coupled architecture
7. architect for empowered teams

## Project
For our demo application we are using a simple calculator because it is easy to test in the unit tests.

Our pipeline consists of 3 stages:
- build
- test
- deploy

#### Build stage
In this stage the calculator application is built.
#### Test stage
In this stage multiple units test for the application are executed.
#### Deploy stage
In this stage the tested calculator application get deployed on a kubernetes cluster.

## Milestones
### 1.Milestone
The first milestone consists of setting up Jenkins X and creating the calculator application.
### 2.Milestone
The second milestone consists of creating the unit tests for the calculator application.
### 3.Milestone
The third milestone consist of setting up the build and test stage of the CD pipeline.

## Responsibilities
Jakob:
- creation of calculator
- Docker build
- deploy stage

Simon:
- setup of Jenkins X
- creating unit tests
- deploy stage
