# Ansible Ubuntu Server 16.04 basic config and Docker.

Decided to put my playbooks online for safe keeping. This playbook configures a basic Ubuntu 16.04 Server and installs Docker.
Plan is to expand the playbooks over time.

If you're looking to use this playbook as is, just clone the repo and run:

```ansible-playbook -i hosts ansible_ubuntu_server.yml --ask-become-pass```

Of course don't forget to adjust the hosts file to your own hostname or ip-address.
