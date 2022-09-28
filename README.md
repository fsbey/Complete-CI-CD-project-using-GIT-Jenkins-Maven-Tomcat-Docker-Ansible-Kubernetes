# Complete-CI-CD-project-using-GIT-Jenkins-Maven-Tomcat-Docker-Ansible-Kubernetes

Full CI/CD pipeline using 7 key DevOps tools
Creating a complete CI/CD pipeline to build and deploy a java application 

I will use:

-Git- Local version control system
-GitHub-Distributed version control system 
-Jenkins-CI tool
-Maven- Build tool
-Ansible- Configuration management and deployment tool
-Docker- Containerisation
-Kubernetes- Containerisation tool

1. Code will be committed from the local VCS to the distributed VCS 
2. Code will then be built using CI tool Jenkins(via Maven)
3. As a result of the build, artifacts will be deployed onto the target environment
4. The tool that will enable us to do that is Ansible
5. Ansible will initially deploy on a VM
6. Then it will be deployed on a docker container, before being deployed on K8's 
