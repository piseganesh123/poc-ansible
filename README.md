# poc-ansible
Ansible installation, configuration and practice few simple unix commands

install Ansible following referring - https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-22-04
tested on ubutnu 22 LTS

$ sudo apt update && sudo apt install ansible

$ ansible-playbook site.yml -l localhost

install docker

$ ansible-playbook install-docker.yml -l localhost
