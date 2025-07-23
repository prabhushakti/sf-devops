# sf-devops
## Salesforce DevOps 
<strong>This repository uses TDD principles to automate deployments in salesforce software development.</strong>
<strong> Use GitHub as SVC and CI/CD. </strong>



<img title=TDD width="1600" height="1372" alt="tdd" src="https://lh7-rt.googleusercontent.com/docsz/AD_4nXfWH8Xb0XRfEI5CVzWaPDxzzGsGHght78Lg-tiJcKpXbiE27yTQeWAwZv2oUgHJGXnViHQ13V5r2n9dN68c2zuuGcJwZ5jjijzXPF_zZ7N0w3J_oV4niqZn8PtQEWQxtqlJyIVr60VEiQEtRLSZPIKCP4T1?key=EKZ6QLmJveNRS_xcgynU5g" />

## Deployment Model
<img width="618" height="93" alt="image" src="https://github.com/user-attachments/assets/1b16de1e-4a55-4b72-9a03-5e59f9970a53" />

## Setting Up IDE
1. Install the IDE - https://code.visualstudio.com/download
2. Install Required Extensions: 
   # code --install-extension myextension.vsix
   Required extensions - mhutchie.git-graph, github.vscode-github-actions, salesforce-extension-pack, jira
3. Authenticate with sfdx project > authorize with an org > verify code manifest file > retrive source code.
4. Authenticate with GitHub and push the code to GitHub (git add . ; git commit -m "test xyz" ; git push -u origin master) 
5. Updates will be seen in the relevant project in Jira thanks to GitHub Pipeline/Actions.



