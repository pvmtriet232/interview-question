## 1. What is DevOps
DevOps is nothing more than breaking the wall between development and operation to improve the efficiency and quality of software development, delivery, and deployment by using various of DevOps tools to achieve automation, continuous integration, delivery, deployment
The primary goal of DevOps is to foster teamwork between the development and operations teams so that they can may collaborate easily across the whole software development life cycle
## 2. What is a DevOps Engineer ?
DevOps engineers collaborate closely with IT operations teams, software developments, and other stakeholders to guarantee the effective delivery of software products.
To increase the efficiency and quality of software development, they are in charge of implementing automation, continuous delivery / deployment (CI/CD) practises.
Locate and resolve issues that arise thoughout the development process.
DevOps engineers often have extensive backgrounds in IT operations, systems administrator, software development, scripting, automation, and cloud computing skills. 
## 3. What do you know about DevOps and it's role?
Nowaday, Technologies are growing incredibly fast, end users have less toleration for downtime of an application. That why we need DevOps to minify the human errors, and automation, continuous development, testing, integration, deployment, monitoring of the software throughout the lifecycle.
## 4. Which are some of the most popular DevOps tools?
Git, Jenkins, Ansible, Docker, Chef, Puppet, Selenium
## 5. What are the different phases in DevOps?
Plan
Code
Build 
Test
Integrate
Deploy
Operate
Monitoring
## 6. Mentions some of the core benefit of DevOps
### technicle benefits
> Continuous software delivery
> Less complex problems to manage
> Early detection and faster correction of defects
### production benefits:
> Faster delivery of features
> Stable operating environments
> Improve communication and collaboration between teams
## 7. What is the difference of CI and CD
CI:
. ensure the code can be safely deploy on to production
. Ensure business applications and services function as expected
. Delivers every change to a production-like environment through rigorous automated testing
CD:
.Every change that pass the automated tests is deployed to production automatically
. Make software development and release process faster and more robust
. There is no explicit approval from a developer and requires a developed culture of monitoring
## 8. What is the role of configuration management in DevOps
. Enables management of and changes to multiple systems.
. Standardizes resouces configurations, which in turn, manage IT infrastructure.
. It helps with the administration and management of multiple servers and maintain the integrity of the entire infrastructure.
## 9. How does continuous monitoring help you maintain the entire architecture of the system?
. Continuous monitoring in DevOps is the process of detecting, indentify and report any faults or threat in the entire infrastructure of the system.
. Ensure that all services, applications, and resources are running in the servers properly.
. Monitors the status of servers and determines if the applications are working correctly or not.
. Enables continuous audit, transaction inspection, and control monitoring.
## 10. What is the role of AWS in DevOps
> AWS has the following role in DevOps:
. Flexible services, provide ready-to-use, flexible services without the need to install or set up the software.
. Build for scale: You can manage a single instance or scale to thousands using AWS services.
. Automation: AWS lets you automate tasks and processes, giving you more time to innovate
. Secure: using IAM, you can setup user permissions and policies.
. Large partner ecosystem: AWS supports a large ecosystem of partners that integrate with and extend AWS services.
## 11. Name three important DevOps KPIs
. Meantime to failure recovery: This is a average time taken to recover from a failure.
. Deployment frequency: The frequency in which the deployment occurs.
. Percentage of failed deployments: The number of times the deployment fails.
## 12. Explain the term "Infrastructure as code" as it relate to configuration management.
. Writing code to manage configuration, deployment, and automate provisioning.
. Managing data centers with machine-readable definition files, rather than physical hardware configuration.
. Ensuring all servers and other infrastructure components are provisioned consistently and effortlessly.
. Administering cloud computing environments, also known as Infrastructure as a Service (IaaS)
## 13. How is IaC implemented using AWS
. Start by talking about old-age mechanisms of writing commands onto script files and testing them in a separate environment and how this approach is being replaced by IaC. Similar to the codes written for other services, with the help of AWS, IaC allow developers to write, test and maintain infrastructure entities in a descriptive manner, using format such as JSON or YAML. This enable easier development and faster deployment of infrastructure changes.
## 14. Why Has DevOps gained prominence over the last few years?
. ...
## 15. What are the benefits of using version control?
. All team members are free to work on any file at anytime with the version control system. Later on, VCS allows the team to integrate all of the modifications into a single version.
. The VCS ask to provide a brief summary of what was changed every time we save a new version of the project. We also get to examine exactly what was modified in the content of the file. As a result, we will be able to see who made what changes to the project.
. inside the VCS, all the previous variants and versions are properly stored. We will be able to request any version at any moment, and we will be able to retrieve a snapshot of the entire project at our fingertips. 
. A VCS that is distributed, such as GIT, lets all the team members retrieve a complete history of the project. This allows developers or other stakeholders to use the local Git repositories of any of the teammates even if the main server goes down at any point in time.
## 16. Describe the branching strategies you have used.
. Release branching - we can clone the develop branch to create a Release branch once it has enough functionality for a release. This branch kicks off the next release cycle, thus no new features can be contributed beyond this point. The things that can be contributed are documentation generation, bug fixing, and other release-related tasks. The release is merged into master and given a version number once it is ready to ship. It should also be merged back into the development branch, which mah have evolved since the initial release-related tasks. The release is merged into msater and given a version number once it is ready to ship. It should also be merged back into the development branch, which may have evolved since the initial release.
. Feature branching - this branching model maintains all modifications for a specific feature contained within a branch. The branch gets merged into master once the feature has been completely tested and approved by using tests that are automated.
. Task branching - In this branching model, every task is implemented in its respective branch. The task key is mentioned in the branch name. We need to simply look at the task key in the branch name to discover which code implements which task.
## 17. Can you explain the " Shift left to reduce failure" concept in DevOps?
Shift left is a DevOps idea for improving security, performance, and other factors. Let us take an example: if we look at all of the processes in DevOps, we can state that security is tested prior to the deployment step. We can add security in the development phase, which is on the left , by employing the shift method. We can integrete with all phases, including before development and during

