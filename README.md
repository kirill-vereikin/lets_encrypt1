Ansible roles for apache and letsencrypt-server
===================================
Before you playing a book, you need to be sure that you changed vars in inventory.ini

Roles for Ubuntu 14.04

Deploy front:

```
ansible-playbook -i inventory.ini play.yml -t front
```

Deploy letsencrypt-server

```
ansible-playbook -i inventory.ini play.yml -t letsencrypt-server
```
