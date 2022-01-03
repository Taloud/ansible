# Ansible
Welcome to my ansible full instalation for ubuntu

## Install process
```
sudo apt-get install git
sudo apt-get install ansible
git clone https://github.com/Taloud/ansible.git
cd ansible
ansible-playbook -t install --ask-vault-pass local.yml
```

Manually `PlugInstall` in neovim.

Restart computer then to ensure everithing is fine.

For now zsh is still not by defaut dunno why so have to `chsh -s $(which zsh)` then restart once.
