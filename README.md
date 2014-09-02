# Dev environment

## To set up (as root):
```bash
apt-get install git ansible
git clone https://github.com/samholman/dev-env-provisioning.git ~/provisioning
cd ~/provisioning
ansible-playbook playbook.yml -i hosts
```
