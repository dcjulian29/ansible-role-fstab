# Ansible Role: fstab

[![Lint](https://github.com/dcjulian29/ansible-role-fstab/actions/workflows/lint.yml/badge.svg)](https://github.com/dcjulian29/ansible-role-fstab/actions/workflows/lint.yml) [![GitHub Issues](https://img.shields.io/github/issues-raw/dcjulian29/ansible-role-fstab.svg)](https://github.com/dcjulian29/ansible-role-fstab/issues)

This an Ansible role to control active and configured mount points

## Requirements

- Active Internet Connection.

## Installation

To use, use `requirements.yml` with the following git source:

```yaml
---
roles:
- name: dcjulian29.fstab
  src: https://github.com/dcjulian29/ansible-role-fstab.git
  version: main
  ```

Then download it with `ansible-galaxy`:

```shell
ansible-galaxy install -r requirements.yml
```

## Dependencies

None
