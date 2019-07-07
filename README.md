# Ansible Role: fqdn

[![Build Status](https://img.shields.io/travis/arillso/ansible.fqdn.svg?branch=master&style=popout-square)](https://travis-ci.org/arillso/ansible.fqdn) [![license](https://img.shields.io/github/license/mashape/apistatus.svg?style=popout-square)](https://sbaerlo.ch/licence) [![Ansible Galaxy](https://img.shields.io/badge/ansible--galaxy-fqdn-blue.svg?style=popout-square)](https://galaxy.ansible.com/arillso/fqdn) [![Ansible Role](https://img.shields.io/ansible/role/d/25136.svg?style=popout-square)](https://galaxy.ansible.com/arillso/fqdn)

## Description

The Ansible role sets fqdn, which fell in the inventory. It works with Linux and Windows.

## Installation

```bash
ansible-galaxy install arillso.fqdn
```

## Requirements

None

## Role Variables

None

## Dependencies

None

## Example Playbook

```yml
- hosts: all
  roles:
    - arillso.fqdn
```

## Author

- [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2019, Arillso
