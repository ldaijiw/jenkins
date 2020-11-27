# Jenkins and CI

## CI/CD

**C**ontinuous **I**ntegration and **C**ontinuous **D**elivery (or **D**eployment)

- One of best practices for DevOps teams to implement 

**Continuous Integration**

Coding philosophy and set of practices to establish a consistent and automated way to build, package, and test applications
- Teams can implement small changes and very swiftly receive feedback to see if there are any errors or bugs
- The consistency of the integration process enables teams to commit code changes more frequently, leading to better collaboration and software quality


**Continuous Delivery**

Automates the delivery of applications to selected infrastructure environments
- Most teams work with multiple environments (development, testing, and production)
	- CD ensures that there is an automated way to push code changes


CI/CD require continuous testing as the objective is to deliver quality applications and code to users

A mature CI/CD DevOps practice has the option of implementing continuous deployment where application changes run through the CI/CD pipeline and passing builds are deployed directly to production environments 

## Jenkins

**Jenkins is an open source automation server which enables teams to build their own CI/CD pipelines**

Jenkins receives any code changes from a Github repository via a webhook (any changes are set up to be automatically sent to Jenkins, rather than Jenkins constantly checking for changes)

Jenkins then sends the code to an _Agent Node_ (i.e. the testing environment) where the code is
- Setup
- Tested

If anything fails, Jenkins provides feedback to the Dev team so they can make any necessary changes