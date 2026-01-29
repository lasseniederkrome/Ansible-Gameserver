# Ansible-Gameser::r

Setup for setting up a server with ansible + docker container for different gameservers, e.G. Hytale, Minecraft, Terraria

# How do we run it?

1. SSH Agent
   eval "$(ssh-agent -s)"
   ssh-add /home/lasse/.ssh/strato612

2. Correct playbook Command:
   ansible-playbook --user root roles/common/playbook_hello.yml
