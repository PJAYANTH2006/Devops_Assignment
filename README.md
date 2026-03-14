SDLC Assignment – Smart-Attend Mobile Application
Project Overview

This repository contains the submission for the SDLC & DevOps Fundamentals Assignment.
The assignment involves an analysis of software development methodologies and how Agile development can be employed in the management of changes in software development, as illustrated in the scenario.
The scenario involves the development of a Smart-Attend Mobile Application, which is a system designed to automate student attendance using Geo-fencing technology. The system automatically takes attendance upon entry into the classroom area.
In the course of developing the system, a new requirement is introduced, where the system needs to be enhanced to include Biometric Face ID technology in order to prevent proxy attendance. The assignment involves an analysis of the changes in the requirements and how Agile development can be employed in the management of changes in software development.
Repository Contents
The repository includes the following documents:
Task1_Analysis.pdf
The document provides an analysis of why the Waterfall model fails to work when new requirements are introduced during the project development phase.
Task2_AgileScrum.pdf
The document provides a description of how the Agile Scrum model works for managing changes to project requirements using the iterative approach to project development.
SprintBacklog.xlsx
The document includes a Sprint Backlog prepared for Sprint 1, which includes user stories, priorities, and estimated development hours for the project.
README.md
The document provides a description of the project and the role of CI/CD for deploying application updates to the user base.
Smart-Attend System Workflow
The Smart Attend application works as follows:
Student logs into the mobile application using their university credentials.
The application tracks the location of the student using Geo-fencing technology.
Once the student enters the classroom, the application verifies the student’s identity using Face ID technology.
Once the student’s identity is verified, the application automatically checks the attendance of the student.
The faculty member can view the attendance of the students using a dashboard.
### Why Agile Scrum Was Used

The main reason Agile Scrum was used for this project is that other development approaches, such as the Waterfall model, are not effective when there are changes to the requirements. The addition of biometric verification will need to be redesigned if the Waterfall model is used.

The Agile Scrum model will be effective for this project since it allows for changes to be added to the requirements by breaking the development process into short development cycles known as Sprints.

The benefits to be achieved by using the Scrum model include:

Flexibility to add new requirements

Faster delivery of new features

Constant improvement through testing

Stakeholders will be involved from the onset

Better collaboration between development teams

The development process will be divided into two Sprints, each taking 2 weeks. 

Sprint 1 will be for the development of the MVP with features such as login, UI, and Geo-fencing. 

Sprint 2 will be for the addition of Face ID biometric verification.
Role of CI/CD for the Smart Attend Application

CI/CD, or Continuous Integration and Continuous Deployment, is a crucial DevOps practice for the automation of the software building, testing, and deployment process. 

**Continuous Integration**

The process of Continuous Integration ensures the following:

*   **Code building** - When the developers push their changes to the repository, the code is built automatically.
*   **Testing** - When the changes are pushed to the repository, the automated tests for the changes are executed automatically. This ensures the detection of any issues related to the integration of the new changes. This way, there is no chance for errors to accumulate during the software development process. 

**Continuous Deployment**

The process of **Continuous Deployment** ensures the following:

*   **Release of the new changes** - After the successful testing of the changes, the new changes are released to the users. 

The advantages of using the CI/CD process for the Smart Attend Application are as follows:

*   **Faster release of the new features for the Sprint** - When the CI/CD process is implemented, the new features for the Sprint release can be delivered to the users faster. 
*   **Immediate release of the new features** - When the
