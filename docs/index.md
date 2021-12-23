# Welcome to the course assessment for building cloud-native applications

This course is composed up of the below sections:

### Section 1 [15 Points]
Multiple choice Questions

### Section 2 [30 Points]
Lab Exercise

### Time Given
3 Hours

## Section 1 - MCQs

```markdown
Question 1. Which one of the following is an orchestration software which can be used for scaling containers?

A. Azure Batch.
B. Azure Kubernetes.
C. Azure Data Factory.
D. Azure key vault.


Question 2. What is the basic operational unit of Kubernetes?

A. Pod
B. Container
C. Nodes
D. Task


Question 3. Which one of the following can be done for a container based application using Azure Kubernetes?

A. Making container scalability easy.
B. Make workloads portable.
C. Build more extensible apps.
D. All of the above.


Question 4. Which one of the following helps to set up cluster autoscaler for adding capacity as per demand?

A. Virtual nodes
B. VM Scale sets
C. Container
D. None of the above.

Question 5. Which one of the following is incorrect regarding Azure Kubernetes?

A. Azure Kubernetes does not mandatorily need resources to be created in cloud.
B. Azure Kubernetes manages and makes deployment of container based applications easy.
C. Azure Kubernetes helps in automatic scheduling of container based application.
D. None of these.
View Answer


Question 6. Choose the correct option.

A. Azure Kubernetes is an open source platform.
B. etcd is used to maintain the state of Kubernetes cluster and configuration.
C. Both A and B.
D. Neither A nor B.
View Answer


Question 7. Choose the wrong statement regarding Azure Kubernetes.

A. Use of Azure Kubernetes demands a ver low minimum monthly charge.
B. It can integrate with Visual Studio Code.
C. It provides elastic scalability.
D. None of these.
View Answer


Question 8. Which one of the following is correct regarding clusters of Azure Kubernetes?

A. Cluster name need not be unique within the selected resource group.
B. Azure CLI can be used to create clusters.
C. Both A and B.
D. Neither A nor B.
View Answer


Question 9. Choose the correct option.

A. It can integrate with Azure Active Directory.
B. Role based access control is possible in Azure Kubernetes.
C. Both A and B.
D. None of these.
View Answer


Question 10. Which one of the following permission must be given to the service principal to establish authentication between AKS and ACR?

A. ACR.Write
B. ACR.Push
C. ACR.Pull
D. B and C

Question 11. How do I add a message to a commit?
A. $ git message "Fix error in xxxx"
B. $ git add "Fix error in xxxx"
C. $ git commit "Fix error in xxxx"
D  $ git commit -m "Fix error in xxxx"

Question 12. Which of the following commands is used to tag a Helm chart?
A. helm chart update
B. helm chart push
C. helm chart save
D. helm chart tag

Question 13. Where does AKS store Helm release configuration?
A. Azure Key Vault
B. K8S secrets
C. GitHub Secrets
D. B and C

Question 14. Fill in the missing command syntax:
helm install -n ns-intel <param-1> <param-2>
A. Param-1: release name, Param-2: pod name
B. Param-1: release name, Param-2: chart name
C. Param-1: pod name, Param-2: release name
D. Param-1: chart name, Param-2: release name

Question 15. How can you expose K8S deployments externally?
A. PVCs
B. Services
C. Ingress
D. B and C

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

The proof of executions for this lab are requested to be uploaded to the below location:
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

