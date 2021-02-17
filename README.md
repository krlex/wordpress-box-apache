# Wordpress
===========

## Wordpress in Vagrant and Ansible

```
vagrant up
```
and see ipaddress from Vagrantfile
in this case is `192.168.88.11`

## Warning
if shows any error just do again provision and it will fix by himself

```
vagrant provision
```

## Tested

- Debian 10 (Buster)
- Ubuntu 18.04 (Bionic)
- Fedora 33
- CentOS 8

to run on direct server command is:
```
ansible-playbook -i inventory/localhost playbook.yml -c local
```
