ansible-cozy-playbook
=====================

Short playbook to show how ansible-cozy-role can be used on an existing server.

Requirements
------------

This playbook requires Ansible 1.4 or higher. It has been tested for Debian 7 system.

Another requirements:
- NodeJS role from [AnsibleShipyard/ansible-nodejs](https://github.com/AnsibleShipyard/ansible-nodejs)
- CouchDB role from [guillaumededrie/ansible-role-couchdb](https://github.com/guillaumededrie/ansible-role-couchdb)
- cozy role from [zaurky/ansible-cozy-role](https://github.com/zaurky/ansible-cozy-role)

Installation
------------

Run:
```
$ ansible-galaxy install -r galaxy.yml -p ./roles
```

Execution
---------

Run:
```
$ ansible-playbook playbook.yml
```


Licence
-------

GNU GPL v2
