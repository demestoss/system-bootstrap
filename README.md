```
sh ./install.sh
ansible-playbook debian.yml -t install --ask-become-pass --ask-vault-pass
ansible-playbook arch.yml -t install --ask-become-pass --ask-vault-pass

or

ansible-playbook debian.yml -t desktop --ask-become-pass --ask-vault-pass
ansible-playbook arch.yml -t desktop --ask-become-pass --ask-vault-pass
```
