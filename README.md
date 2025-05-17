>>>>>>>  HEAD
#Java Web app Deployment with AWS CI/CD

In this project I combined Java web App delopment with AWS CI/CD tools!

## Table of Contects 

<br>
- [ Introduction ] ( #Introduction )
- [ Technologies ] ( #Technologies )
- [ Contact ] ( #Contact )
- [ Concusion ] ( #Concusion )

<br>

## Introduction

This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

## Technologies
Here are the tools used in this project:

- **Amazon EC2**: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
- **Key pairs**, SSH connections, Git, Maven and Java.
- **VSCode**: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
- **GitHub**: All my web app code is stored and versioned in this GitHub repository.
- **AWS CodeArtifact**: All my dependencies and packages that are needed for my webapp is stored in codeArtifact.
- **AWS CodeBuild**: CodeBuild is a CI service, will take over my build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
-  **AWS CodeDeploy**: CodeDeploy will automate my deployment process across EC2 instances.
-  **AWS CodePipeline**: Once it's rolled out, CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.

<br>

## Code
**mvn compile -s settings.xml** - Compiles the code from the webapp into code that the machine can understands. It also scans through the webaoo code creates a snapshot of the dependencies and packages that it thinks the project needs into the CodeArtifact repository.

<br>

## Contact
If you have any questions or comments about the my CI/CD project, please contact:
Dennis Morrison  - [Dtech2133@gmail.com](mailto:dtech2133@gmail.com)

<br>

## Conclusion

Thank you for exploring this project! I'll continue to build this pipeline and apply my learnings to future projects
=======
# webapp-project
Java Web app set up on an EC2 instance. 
>>>>>>> main
