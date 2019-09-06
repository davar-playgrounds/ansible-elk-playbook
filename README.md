Ansible ELK Playbook

This Playbook is for setting up version 7.X of the ElK Stack.
Playbook set up ELK stack with Filebeat and Metricbeat for server monitoring.

How to:
1. Install Ansible on your machine.
2. Clone this repo.
3. Edit your Ansible hosts file in ansible.cfg, and add an 'ELK' entry for the server you wish to install ELK on.
4. CD into the directory with playbook, and run: ansible-playbook site.yml --ask-become-pass -s -vvv

This Playbook was tested on Ubuntu 18.04 LTS, for ELK version 7.X
This PLaybook include basic installation of ELK Stack and not include deep confuguration of ELK. If you need it read the docs.