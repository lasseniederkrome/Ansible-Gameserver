# Ansible-Gameservr

Setup for setting up a server with ansible + docker container for different gameservers, e.G. Hytale, Minecraft, Terraria

# How to run?

0. First run: Set up root ssh key exchange, so we can connect ssh as root@server

1. SSH Agent
   eval "$(ssh-agent -s)"
   ssh-add ~/.ssh/strato612

   This is necessary for ansible if we use pw-encrypted ssh key

2. Correct playbook Command:
   ansible-playbook --user root roles/common/playbook_hello.yml
