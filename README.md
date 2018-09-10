Ansible Role Wordpress
======================================

Ansible role to manage wordpress instances.

Role Variables
--------------

- `wordpress_config`:
Dictionary with wordpress configuration. See
[default vars file](defaults/main.yaml)

- `wordpress_version`:
Version to let the role choose the right template for the config file.

Example Playbook
----------------

```
- hosts: all
  roles:
    - role: vundb-wordpress
      wordpress_config:
        db_name: wordpress
        db_user: wordpress
        db_password: wordpress
        table_prefix: wp_
```

License
-------

MIT

Author Information
------------------

- You can find more roles in my GitHub channel [vundb](https://github.com/vundb)
- Follow me on Twitter [@vundb](https://twitter.com/vundb)
