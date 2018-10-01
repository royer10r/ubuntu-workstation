# ubuntu-workstation
Ubuntu 18.04 workstation setup

# Install ansible
- sudo apt install software-properties-common
- sudo apt-add-repository ppa:ansible/ansible
- sudo apt install ansible

# Run ansible-pull to finish setup
sudo ansible-pull -U https://github.com/royer10r/ubuntu-workstation.git
