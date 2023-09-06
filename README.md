# Deployment automation

## Used tools:
- **_CI-CD_**: Jenkins
- **_IaC_**: Ansible
- **_Containerization_**: Docker
- **_SCM_**: GIT
- **_Web Server_**: NGINX
- **_Languages_**: Bash (executable script), YAML (Ansible configuration), Groovy (jenkinsfile)

## Detailed project information
- script for collect information about the system (script.sh) has been developed
- Ansible playbook  (script.yml) for execution script has been developed
- Jenkins builds image based on Dockerfile (docker/Dockerfile) and pushes it to DockerHub repo
- Ansible playbook (docker.yml), which prepares the target system to launch the container with the nginx Web-server, pulls the image from Dockerhub, mounts the directory with the default page {the result of the script execution} has been developed
- For tracking changes in the GitHub repository webhook (using ngrok utility) was configured for any push to the repository. 

# Contact information
Yuliya Varavko

yuliya.varavko@gmail.com
www.linkedin.com/in/yuliya-varavko
+375(29)3864588
