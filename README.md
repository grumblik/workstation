# workstation
apt install dirmngr <br>
apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367 <br>
apt update
apt install ansible
ansible-playbook install.yml --limit localhost
