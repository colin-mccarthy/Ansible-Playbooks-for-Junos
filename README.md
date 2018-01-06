# Ansible-Playbooks-for-Junos

Mission

Ansible-Playbooks-for-Junos is a repository of Ansible Playbooks for Juniper devices.

To use, download the .zip and extract the contents or clone the repository by typing

```git clone https://github.com/colin-mccarthy/Ansible-Playbooks-for-Junos.git```



To use Ansible on Juniper devices you need to enable the netconf service on your Juniper device with this command.

```set system services netconf ssh```

Also I recommend you upgrade to Ansible 2.3 to resolve any issues or bugs you might run into.


Good Practices:

Always name your playbooks with a .yml at the end. This is required if you ever want to use your playbooks with Ansible Tower. 
