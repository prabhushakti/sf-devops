# sf-devops
## Salesforce DevOps 
<strong>This repository uses TDD principles to automate deployments in salesforce software development.</strong>
<strong> Use GitHub as SVC and CI/CD. </strong>

[![Click to Watch]((https://www.gitkraken.com/wp-content/uploads/2022/06/Using-Jira-and-GitHub_Hero-2048x1024.jpg.webp))](https://vimeo.com/1103750436)
[![Current Progress Video](https://www.gitkraken.com/wp-content/uploads/2022/06/Using-Jira-and-GitHub_Hero-2048x1024.jpg.webp)](https://vimeo.com/1103750436) 



## Deployment Model
<img width="618" height="93" alt="image" src="https://github.com/user-attachments/assets/1b16de1e-4a55-4b72-9a03-5e59f9970a53" />
<img title=TDD width="1600" height="1372" alt="tdd" src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfWH8Xb0XRfEI5CVzWaPDxzzGsGHght78Lg-tiJcKpXbiE27yTQeWAwZv2oUgHJGXnViHQ13V5r2n9dN68c2zuuGcJwZ5jjijzXPF_zZ7N0w3J_oV4niqZn8PtQEWQxtqlJyIVr60VEiQEtRLSZPIKCP4T1?key=EKZ6QLmJveNRS_xcgynU5g" />

## Setting Up IDE
1. Install the IDE - https://code.visualstudio.com/download
2. Install Required Extensions: 
   #code --install-extension myextension.vsix
   Required extensions - mhutchie.git-graph, github.vscode-github-actions, salesforce-extension-pack, jira
3. Authenticate with sfdx project > authorize with an org > verify code manifest file > retrive source code.
4. Authenticate with GitHub and push the code to GitHub (git add . ; git commit -m "test xyz" ; git push -u origin master) 
5. Updates will be seen in the relevant project in Jira thanks to GitHub Pipeline/Actions.

## Jira Configuration
* Ensure GitHub plugins are installed: Git Integration for Jira.

## Installing SF Command
* For Linux - download the tar file in /opt directory.
* Extract and update the path by adding the bin directory into .bashrc file.

## Creating a SF Project
* control + shift + p then create project with manifest
* authorize with org
* retrive source from package.xml (pull metadata from code): sfdx force:source:retrieve -manifest path/packge.xml
* test using sfdx force:apex:test:run --tests etc. etc.
* push the code (soruce to org) 

