[![Build Status](https://travis-ci.com/Mireiawen/ansible-role-skel.svg?branch=master)](https://travis-ci.com/Mireiawen/ansible-role-skel) [![Ansible Galaxy](https://img.shields.io/badge/Ansible%20Galaxy-mireiawen.skel-blueviolet)](https://galaxy.ansible.com/mireiawen/skel)


# Skel

Install customized bash init scripts and other dotfiles to `/etc/skel` and `/root`

## Requirements

None.

## Role Variables

The system name should be set via the `system_name` variable. The system name is included into the shell prompt and defaults to `Default-System`.

## Dependencies

None.

## Example Playbook

    - hosts: "servers"
      roles:
         - "mireiawen.skel"

## License
MIT, see `LICENSE`

