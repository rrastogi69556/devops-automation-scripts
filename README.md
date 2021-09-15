# devops-automation-scripts
This contains the scripts which helps automatic build and deploy to the environment.

- It contains a sample script : deploy.yml which is Ansible scipt to be taken from artifactory/nexus and deploy on the docker environments. 
- It is assumed to be integrated with Jenkins -> Configure -> Build -> Add Ansible playbook -> "deploy.yml" 
- scripts.sh file is used to work along with ansible "deploy.yml" file during Jenkins build so that it finds latest artefact (package) from the nexus/artifactory and uses along with deploy.yml to deploy on docker environments.
