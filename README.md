# Ansible
Welcome to my ansible full installation for ubuntu

## Install process
```
sudo apt-get install git
sudo apt-get install ansible
git clone https://github.com/Taloud/ansible.git
cd ansible
ansible-playbook -t install --ask-vault-pass local.yml --ask-become-pass
```

Manually `PlugInstall` in neovim. 

For now zsh is still not by defaut, so have to `chsh -s $(which zsh)` then restart once.

Restart computer then to ensure everything is fine.
