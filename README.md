# schoolmg_ansible

Run playbook

Create file http/commun/inventaire.ini


Go to http/test

```
cd http/test
ansible-playbook -i ../../commun/inventaire.ini  --become --ask-become-pass --ask-vault-pass playbook-install.yml
```
