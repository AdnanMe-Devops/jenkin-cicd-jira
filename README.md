# jenkin-cicd-jira
Create a Jenkins CICD Pipeline to Publish Build Results into Jira
Integrating Jenkins and Jira together provides  with a solution that can be used to report issues as they happen for any CICD pipeline build job. Jenkins can be configured to publish any and all build results, artifacts, and/or bugs directly into Jira. DevOps teams can then use Jira to project manage the required fixes necessary to get their applications into production.

In this PROJECT will launch a Jenkins and Jira CICD and issue management environment using Docker containers on a provided EC2 instance and will then configure a Jenkins build pipeline to build, compile, and package a sample Java servlet web application, with the resulting build information being published automatically into Jira and  then use Jira to observe the details about the Jenkins build just performed.


Note:  will be required to generate a trial license on the Atlassian website, which is used to activate the Jira application. 

 Objectives

Install and configure a Jenkins and Jira CICD and issue management environment using Docker containers 
Configure Jenkins with the Gradle tool to perform the core build and packaging for a sample Java servlet web application
Configure Jenkins with the Jira Pipeline Steps plugin for automated issue management 
Create and set up a Jenkins build pipeline using a Jenkinsfile stored within a GitHub repo
Kickoff a Jenkins build and review the build results
Use the Jira administration web console to manage the issues raised automatically by the Jenkins pipeline build


Use Docker Compose to launch the following Docker containers:
Jenkins
Jira
Socat
Using a browser, administer and configure Jenkins - installing the required plugins. Connectivity to Jenkins will be done via the cicd.platform.instance Public IP address 
Using a browser, administer and configure Jira. Connectivity to Jira will be done via the cicd.platform.instance Public IP address 
Create a Jenkins build pipeline and configure it to build a sample Java servlet web application hosted on GitHub
Execute the Jenkins build pipeline and confirm that it has completed successfully, registering a new Jira ticket automatically, and attaching the Gradle build log file
Use the Jira administration console to manage the ticket raised by the Jenkins pipeline build process
