Roles
=====

Role | Purpose
---- | -------
app-tier | This role is used to configure the Tomcat webserver component of the 3-Tier
base-config | This role performs a basic configuration on the server: enable sudo, enable repos, install base tools
config-tower | This role configures Ansible Tower with the project, templates and credentials nedded for the Homework
db-tier | This role is used to configure the PostgreSQL component of the 3-Tier
lb-tier | This role is used to configure the HAProxy component of the 3-Tier
osp-facts | This role gets the facts from OpenStack in order to configure the instances
osp-instance-delete | This role is used to delete the server instances of the OpenStack cloud
osp-servers | This role is used to create the server instances of the OpenStack cloud
osp-setup | This role sets up the OpenStack Platform with the base configuration needed to create the QA instances
setup-workstation | This role is used to set up the workstation to work with the OpenStack cloud

