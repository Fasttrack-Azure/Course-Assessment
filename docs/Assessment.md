# Welcome to the course assessment for automating application deployment to AKS using GitHub Actions

This course is composed up of the below sections:

### Section 1 [20 Points]
Multiple choice Questions

### Section 2 [30 Points]
Lab Exercise

### Time Given
3 Hours

## Section 1 - MCQs

```markdown
Question 1
Question 
a. 
b. 
c. 
d. 

```

## Section 2 - Lab Exercise

```markdown

**Lab Title:** Develop an automated workflow using GitHub Actions to deploy an application with React frontend and .NET Core Web API backend to Azure Kubernetes Service


**Description:**
This lab covers the below dimensions of AKS and GitHub:
1. AKS Operations
2. GitHub Actions
3. HELM 3
4. Integration with Container Registry
5. Integration with Azure Key Vault
6. Integration with Azure Storage

The proof of executions for this lab are requested to be uploaded to the lelow location:
https://1drv.ms/u/s!AjKtnZen93C0nRWh0myuo4CTCqyH?e=haO08c

**Steps:**

**Step 1:**
- Clone a sample React + .NET Core Web API application (Dockerized) locally using VS Code or Visual Studio. Sample code: https://github.com/Fasttrack-Azure/Course-Assessment.git
- You may feel free to you any other codebase as per your convenience.

**Step 2:**
- Build a docker image locally
- Test and run the image loally
- Retag the image and push it to Azure Container Registry
- Attach a snapshot for the successful push to ACR (CLI logs or Azure Portal)

**Step 3:**
- Create a GitHub workflow to build and push the image to ACR via GitHub Actions
- Test the workflow and attach a snapshot for the successful execution of the above workflow

**Step 4:**
- Add HELM support to the project created in **Step 1**
- Update the GitHub workflow to package the Helm chart and push it to AKS
- Test the workflow and attach a snapshot for the successful execution of the above workflow


**Step 5:**
- Update the Github workflow to install the helm chart in ns-<your-name> namespace
- Test the workflow and attach a snapshot for the successful execution of the above workflow
  
**Step 6:**
- Commit any small change in application frontend to re-run the GitHub Workflow and upgrade your AKS deployment
- Rollback to the previous release via Azure CLI
- Attach a snapshot for helm history command 
  
**Step 7 - Optional:**
- Add an environment variable to the pod defination
- Create the corresponding secret in Azure Key Vault
- Upgrade the deployment using your GitHub workflow
- Test the workflow and attach a snapshot for the successful execution of the above workflow
- Attach a snapshot for the availability of the AKS secret as an environment variable in the pod

```

