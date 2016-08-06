# Ansible Role: Mozilla Firefox

[![Build Status](https://travis-ci.org/tschifftner/ansible-role-firefox.svg)](https://travis-ci.org/tschifftner/ansible-role-firefox)

Installs Mozilla Firefox on Debian/Ubuntu linux servers.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    firefox_version: '45.0'
    firefox_language: 'de'
    firefox_os: 'linux-x86_64'

_Versions after 45.0 do not work in headless mode on Debian!_

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: tschifftner.firefox }

## Supported OS

Ansible          | Debian Jessie    | Ubuntu 14.04    | Ubuntu 12.04
:--------------: | :--------------: | :-------------: | :-------------: 
2.1              | Yes              | Yes             | Yes

## License

[MIT License](http://choosealicense.com/licenses/mit/)

## Author Information

 - [Tobias Schifftner](https://twitter.com/tschifftner), [ambimax® GmbH](https://www.ambimax.de)