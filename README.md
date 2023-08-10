# Ansible

#!/bin/bash

# Instalacja Ansibla
sudo apt update
sudo apt install software-properties-common -y
sudo apt-add-repository --yes --update ppa:ansible/ansible
sudo apt install ansible -y

# Dodanie bieżącego użytkownika do grupy ansible
sudo usermod -aG ansible $USER
