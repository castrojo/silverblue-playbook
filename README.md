# silverblue-playbook

Ansible playbook for managing my Fedora Silverblue workstations, adapted for me!

```
sudo rpm-ostree upgrade
sudo rpm-ostree install ansible
```
Reboot 

```
ansible-galaxy collection install ansible.posix community.general
ansible-playbook -K silverblue.yml -l tien
```
