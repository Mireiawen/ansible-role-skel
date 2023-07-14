![Build Status](https://img.shields.io/gitlab/pipeline-status/mireiawenrose/ansible-roles/skel?branch=master&style=plastic) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.skel-blueviolet?style=plastic)](https://galaxy.ansible.com/mireiawen/skel)

# Skel
Install customized bash init scripts and other dotfiles to `/etc/skel` and `/root`

## Requirements
None.

## Role Variables
 Configuration key   | Description                              | Default value               
---------------------|------------------------------------------|----------------------
 `system_name`       | The system nam, included in shell prompt | `Default-System`

## Dependencies
None.

## Example Playbook
```yaml
- hosts: "servers"
  roles:
  - "mireiawen.skel"
```

## License
MIT, see `LICENSE`
