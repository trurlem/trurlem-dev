Ansible Role - sudoers
=========

A small role for automating sudoers configuration.


Role Variables
--------------

| Variable | Meaning |
|--|--|
| sudoers_custom_content | Content added in `sudoers_custom_file` |
| sudoers_custom_file | Path of the custom sudoers file used (will be created if not there) |

See `defaults/main.yml` for default values.
