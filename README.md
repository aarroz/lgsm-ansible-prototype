To use this script, you need the following things:

1. Access to the Egee.io game server via ssh key
2. Linux (Native, VM, Linux Subsystem for Windows, etc)
3. Ansible

To get started with this script, you'll need to install Ansible. From a terminal, run:

1. ``sudo apt install python-pip``
2. ``sudo pip install ansible``

Once Ansible is installed do these things:

1. Clone this repo
2. Open the ``inventory`` file and replace the ip address with the egee.io ip address (or just egee.io itself)
3. From a terminal in the repo directory, run ``ansible-playbook playbook.yml``
