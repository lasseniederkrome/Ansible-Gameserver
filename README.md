# Ansible-Gameserver
Setup for setting up a server with ansible + docker container for different gameservers, e.G. Hytale, Minecraft, Terraria


# What to do?
We have a passphrase proteced root ssh key

We need to run the first playbook via root with the key

For this, we need an ssh-agent in the background to work, Ansible cant take care of this alone
