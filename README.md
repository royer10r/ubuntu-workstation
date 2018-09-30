# ubuntu-workstation\\
Ubuntu 18.04 workstation setup\\
\\
# Install ansible\\
sudo apt-get install software-properties-common\\
sudo apt-add-repository ppa:ansible/ansible\\
sudo apt-get update\\
sudo apt-get install ansible\\
\\
# Clone the repo\\
git clone https://github.com/royer10r/ubuntu-workstation.git\\
\\
# Run ansible-pull to finish setup\\
sudo ansible-pull -U https://github.com/royer10r/ubuntu-workstation.git\\
\\