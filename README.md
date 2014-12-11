elk-ansible
===========

######Ansible playbook for ELK Stack
 - This playbook currently only works for Ubuntu/Debian boxes.
 - Has been tested on Ansible 1.7.2

This playbook deploys a basic Logstash, Elasticsearch, and Kibana stack. Kibana web is served by Nginx.

Please feel free to open an issue if you would like me to add new features to the playbook like supporting a different version of Java or to add support for RedHat/CentOS box

######To install ELK stack:

  - Change the IP address in the `hosts` file to the IP address of the server you want to install the ELK stack on
  - Run `install.sh` from project's main directory or run `ansible-playbook -i hosts site.yml`