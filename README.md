apt install dirmngr
apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
apt update
apt install ansible

# workstation
ansible-playbook install.yml --limit localhost
