# Ansible toolkit
Hello World!
That's my first code on GitHub, so, enjoy it!

My goal is to expand this repo with my ansible toolkit.
 
## Version 1.0

The 1.0 version brings you a phpIPAM instalation on Azure cloud using Ubuntu 18.04LTS on Azure VM and Azure MySQL (PaaS).

You can also utilize these roles:
- **azure-resourcegroup**: Create a resource group on Microsoft Azure subscription.
- **azure-vm**: Create a virtual machine on Azure.
- **azure-mysql**: Create a MySQL server and database (PaaS) on Azure.
- **webserver-apachephp**: Install Apache and PHP server, and MySQL client to a Linux host (apt).
- **phpipam**: Deploy the [phpIPAM](https://phpipam.net/) application to a Linux host.

To launch it in your environment, edit vars in *phpipam_on_azure-vars.yml* file and then run:
...
$ ansible-playbook ansible/phpipam_on_azure.yml
...