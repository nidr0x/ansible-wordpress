# Ansible Role: WordPress 

Download and install latest WordPress version.

NOTE: Due to a bug found in Ansible 2.5x, you will probably see repeated "<?php" tag along of the file wp-salts.php. I recommend that you review it. 

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-wordpress 
```

## License

MIT / BSD

