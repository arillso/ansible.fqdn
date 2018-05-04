# Ansible Role: fqdn

[![Build Status](https://travis-ci.org/arillso/ansible.fqdn.svg?branch=master)](https://travis-ci.org/arillso/ansible.fqdn) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](https://sbaerlo.ch/licence) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-fqdn-blue.svg)](https://galaxy.ansible.com/arillso/fqdn)

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

## Changelog

### 1.0

* initial commit

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2018, Simon Bärlocher