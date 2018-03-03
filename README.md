# Ansible playbook to install Jenkins with HTTPS
Jenkins+Nginx+SSL by ansible

Installing Jenkins+Nginx+SSL on Ubuntu 16.04 by using Ansible.
You have to specify "server_name" in vars.yml for Let's Encrypt certificate
You also need RSA private key to ssh at target host (mentioned in inv file)
