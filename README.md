# Ansible Role: utils

[![Build Status](https://travis-ci.org/cecepm/ansible-role-utils.svg?branch=master)](https://travis-ci.org/cecepm/ansible-role-utils)

Install some utility apps (`curl`, `debconf`, `dmidecode`, `htop`, `iftop`, `iotop`, etc)

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    utils_packages:
    - curl
    - debconf
    - dmidecode
    - htop
    - iftop
    - iotop
    - pciutils
    - screen
    - sysstat
    - tmux
    - vim
    - wget

## Dependencies

None.

## Example Playbook

Using default value

    - hosts: server
      roles:
      - cecepm.utils

## License

MIT / BSD

## Author Information

This role was created in 2014 by [Cecep Mahbub](http://ngadimin.org/).
