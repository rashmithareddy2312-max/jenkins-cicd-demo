# GitHub and Jenkins Integration Using Continuous Integration

## 1. Introduction

This project demonstrates the integration of GitHub with Jenkins to automate the process of retrieving source code and verifying builds. It introduces the basic concepts of Continuous Integration (CI) used in DevOps.

## 2. Objectives

* To understand the basic concepts of DevOps and Continuous Integration.
* To store project files in a GitHub repository.
* To configure Jenkins to retrieve files from GitHub.
* To automate builds when repository changes are detected.
* To verify build results using Jenkins Console Output.

## 3. Technologies Used

* **GitHub:** Online platform for hosting and managing source code.
* **Jenkins:** Automation server used to run configured build jobs.
* **Java JDK 21:** Java environment used to run Jenkins.
* **HTML:** Used to create the sample web page.
* **Windows:** Operating system used for implementation.

## 4. Project Files

* `index.html` — Sample HTML web page.
* `README.md` — Project documentation.
* `.git` — Git version-control metadata created when the repository is cloned.

## 5. System Workflow

1. Create a repository on GitHub.
2. Add the project files to the repository.
3. Install Java and Jenkins.
4. Create a Freestyle project in Jenkins.
5. Configure the GitHub repository URL and the `main` branch.
6. Configure build steps to display project information and list files.
7. Enable Poll SCM to check the repository for changes periodically.
8. Verify the build result using Console Output.

## 6. Continuous Integration

Continuous Integration is a software development practice in which code changes are integrated frequently and checked through automated processes.

In this project, Jenkins uses Poll SCM to check the GitHub repository for changes. When a new change is detected, Jenkins automatically starts a build.

## 7. Implementation and Testing

The Jenkins job named `GitHub-CI-CD-Demo` is configured to retrieve files from the GitHub repository.

The build steps execute Windows commands to display project information and list the retrieved files.

A change was made to `index.html` and committed to GitHub. Jenkins detected the change during polling and automatically started a new build.

## 8. Results

* GitHub repository successfully connected to Jenkins.
* Project files successfully retrieved.
* Automatic build trigger tested successfully.
* Build result verified through Jenkins Console Output.
* Build #3 completed with the status `SUCCESS`.

## 9. Future Enhancements

* Add automated HTML validation and testing.
* Publish build artifacts.
* Configure deployment to a web server.
* Extend the pipeline with additional testing and deployment stages.

## 10. Conclusion

This project demonstrates a basic Continuous Integration workflow using GitHub and Jenkins. It provides practical experience in source-code management, automated builds, change detection, and build verification.

**Project:** GitHub and Jenkins Integration
**Created by:** Rashmitha

