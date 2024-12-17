# Instructions

```bash
mkdir kali ; cd ./kali/ 
git clone https://github.com/dtrac/vagrant-kali.git
vagrant up

```

## Optional

```bash
vagrant ssh-config > vagrant_ssh_config
ansible-playbook --ssh-common-args="-F vagrant_ssh_config" -i default, playbook.yml
ansible-playbook --ssh-common-args="-F vagrant_ssh_config" -i default, update.yml 
```
