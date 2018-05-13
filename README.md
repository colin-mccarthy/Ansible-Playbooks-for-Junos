# Ansible-Playbooks-for-Junos

Mission

Ansible-Playbooks-for-Junos is a repository of Ansible Playbooks for Juniper devices.

To use, download the .zip and extract the contents or clone the repository by typing

```git clone https://github.com/colin-mccarthy/Ansible-Playbooks-for-Junos.git```



To use Ansible on Juniper devices you need to enable the netconf service on your Juniper device with this command.

```set system services netconf ssh```




With the network changes in Ansible 2.5 you need to set up your group vars for your Junos group like this.

```
ansible_ssh_pass=foo
ansible_network_os=junos
ansible_connection=netconf

```
