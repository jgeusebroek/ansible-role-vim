# Ansible role: vim

An Ansible Role that installs and (globally) configures vim on RedHat/CentOS or Debian/Ubuntu.

## Requirements

None

## Dependencies

None

## Example Playbook

    ---
    - hosts: all
      sudo: yes

      roles:
         - { role: jgeusebroek.vim, tags: ["vim"] }

## Example Variables

    # I prefer vim to be the default editor
    vim_default_editor: true

    # Add your config values
    vim_config:
      - "syntax enable"

## License

MIT / BSD

## Author Information

This role was created in 2015 by [Jeroen Geusebroek](http://jeroengeusebroek.nl/).