```
sh ./install.sh
ansible-playbook debian.yml install --ask-become-pass --ask-vault-pass
ansible-playbook arch.yml install --ask-become-pass --ask-vault-pass

or

ansible-playbook debian.yml desktop --ask-become-pass --ask-vault-pass
ansible-playbook arch.yml desktop --ask-become-pass --ask-vault-pass
```
