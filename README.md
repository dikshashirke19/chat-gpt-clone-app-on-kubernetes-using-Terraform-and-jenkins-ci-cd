## Lets deploy ChatGPT clone on k8s using Jenkins and ci/cd with Jenkins

- Step 1 → Setup Terraform and configure aws on your local machine
- Step 2 → Building a simple Infrastructure from code using Terraform
- Step 3 → Setup Sonarqube and Jenkins
- Step 4 → ci-cd pipeline
- Step 5 → kubernetes cluster creation using Terraform via jenkins pipeline
- Step 6 → deployment on kubernetes
- Step 7 → Monitering via Prmotheus and grafana
- Step 8→ Destroy all the Infrastructure
---------------------------------------------------------------------

# START
1. First create a directory, and clone the code using
   ```
    git clone https://github.com/xxx-holic-01/chat-gpt-clone-app-on-kubernetes-using-Terraform-and-jenkins-ci-cd.git 
   ```
2. create a different branch for testing as it is not preferred to work with the main branch without full testing.
   ```
   git branch test
   git checkout test
   ```
   then configure your code and push it to your git repo, on the test branch.
----------------------------------------------------------------------

### Now you are all set :))

-------------------------------------------------------------

## 1 Now install and setup terraform
As I am using Rocky Linux 
```
https://sysadminxpert.com/install-terraform-on-rocky-linux-8-or-centos-8/#:~:text=Steps%20to%20Install%20Terraform%20on%20Rocky%20Linux%208,5%3A%20Install%20Terraform%20Step%206%3A%20Verify%20the%20Installation
```
## Visit AWS Console and configure a IAM user 
![image](https://github.com/xxx-holic-01/chat-gpt-clone-app-on-kubernetes-using-Terraform-and-jenkins-ci-cd/assets/101506676/a0a6598d-fd1f-4810-ab15-eecce429fcbc)



   
