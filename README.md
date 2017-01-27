DirectAdmin
========

This role will install DirectAdmin.

Role variables
--------------

| Variable                             | Description                                                |
| ------------------------------------ | ---------------------------------------------------------- |
| directadmin\_licenseid               | License id, obtained from DA panel                         |

Example playbook
----------------

```
---
- hosts: 127.0.0.1
  roles:
    - role: ansible-role-directadmin
```

To test on a local machine use: ansible-playbook --sudo -i inventory playbook.yml
