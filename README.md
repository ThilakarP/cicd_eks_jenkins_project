# cicd_eks_docker_jenkins_pipeline_automation
CICD jenkins pipeline project to automate the build, store image artifacts and deploy application docker image on EKS cluster
1.  Creation of AWS EKS Cluster and Nodes.
2.  Create a pipeline peoject job in Jenkins.
3.  Stage 1:  Checkout code from github. (git installed on Jenkins Server)
4.  Stage 2:  Build Docker image.  (docker installed on Jenkins Server)
5.  Stage 3:  Push image artifacts to docker hub.
6.  Stage 4.  Deploy app code to EKS cluster using manifest file(deployment.yaml). (kubectl and aws cli installed and configured on Jenkins server)
