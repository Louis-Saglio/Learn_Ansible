This project allows you to deploy a Wordpress blog on a machine with the database on an other one

To launch the deployment :
* Configure your machines IP address in the files `Learn_Ansible/host_vars/machine*.yml`
* Configure your SSH user and private key in the file `ansible.cfg`
* The run `ansible-playbook plays/site.yml` at the root of the project
