# Sam's dev environment
Configures a dev environment from a raw Ubuntu installation.

Automatically sets up:

* [Dotfiles](https://github.com/samholman/dotfiles)
* [samholman.com](https://github.com/samholman/samholman.com)

## Run as root:
```bash
apt-get install -y git ansible && \
git clone https://github.com/samholman/dev-env-provisioning.git ~/provisioning && \
cd ~/provisioning && \
ansible-playbook playbook.yml -i hosts
```

