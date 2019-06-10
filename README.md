# ubuntu_config
##Configure working station for job/home usage

Run the below commands in order to obtain the latest ansible:

sudo apt-get upgrade

sudo apt-get update

sudo apt-get install software-properties-common

sudo apt-add-repository --yes --update ppa:ansible/ansible

sudo apt-get install ansible git

Run the below commands in order to apply tweaks:

mkdir -p ~/dev/ansible/

git clone git@github.com:nakutnyi/ubuntu_config.git ~/dev/ansible/ubuntu_config/

cd ~/dev/ansible/ubuntu_config/

ansible-playbook home.yml
