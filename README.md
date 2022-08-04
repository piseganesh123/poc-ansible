# poc-ansible
Ansible installation, configuration and practice few simple unix commands

install Ansible following referring - https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-22-04
tested on ubutnu 22 LTS

$ sudo apt update && sudo apt install ansible

$ ansible-playbook site.yml -l localhost

install docker

$ ansible-playbook install-docker.yml -l localhost

TO run ansible on specific node / host, add those server entries in /etc/hosts file 

$ ansible-playbook install-docker.yml -i ./hosts -l <remote-srv-1> --private-key <.id_rsa>

You can remove ansible using 

$sudo apt remove ansible