# learn-ansible

Ansible is developed using python.
To install Ansible on linux, we use a python package manager call PIP. 

# dnf install ansible  ( offers ansible core which is ansible-7 )

Latest and grestest version of ansible is available here :  ( 11.3.0 )
https://pypi.org/project/ansible/

# To install ansible:

```
    $ sudo pip3.11 install ansible
```

### What is inventory ?
    Inventory is a file that has the list of all the vm ip's that needs to be managed by ansible
    all is default group on this file that includes every thing on the file.

### Running ansible commands manually:

    $ ansible -i inventoryFileName all -e ansible_user=ec2-user -e ansible_password=DevOps321  -m ansible.builtin.shell -a uptime

Ansible is all about modules ( from version 2.8, we are referring them as collections ),

