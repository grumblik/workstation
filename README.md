# workstation
apt install dirmngr <br>
apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367 <br>
apt update <br>
apt install ansible git apt-transport-https<br>
git clone https://github.com/grumblik/workstation.git<br>
cd workstation <br>
ansible-playbook --connection=local install.yml -i hosts <br>
