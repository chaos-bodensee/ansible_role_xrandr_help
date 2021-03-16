[![Ansible Galaxy](https://raw.githubusercontent.com/roles-ansible/ansible_role_xrandr_help/main/.github/galaxy.svg?sanitize=true)](https://galaxy.ansible.com/do1jlr/xrandr_help) [![MIT License](https://raw.githubusercontent.com/roles-ansible/ansible_role_xrandr_help/main/.github/license.svg?sanitize=true)](https://github.com/roles-ansible/ansible_role_xrandr_help/blob/main/LICENSE)

 ansible_role_xrandr_help
==========================

### Get it directly from Ansible Galaxy 
```bash
$ ansible-galaxy install do1jlr.xrandr_help
```

 Information
-----------------

Ansible role to install xrandr to controll your monitor setup.

This is realy helpful, if you are using a display manager (eg. i3wm) that comes without a dedicated display control center (like gnome).

 Variables:
-----------------

| Variable Name | Default Value | Function |
| ------------- | ------------- | -------- |
| ``install_graphical_application:`` | ``true`` | Install graphical xrandar applications like arandr |
| ``install_autorandr_application:`` | ``true`` | Install autorandr |
| ``submodules_versioncheck:`` | ``false`` | Perform simple versionscheck *(``true`` is recomended)* |

 Testing
---------
This ansible role is tested with some simple linting tests and some other github actions:

| Status | Marketplace |
| ------ | ----------- |
| [![Ansible Lint check](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-linting-check.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-linting-check.yml) | [ansible-lint](https://github.com/marketplace/actions/ansible-lint) |
| [![Yamllint GitHub Actions](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/yamllint.yaml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/yamllint.yaml) | [yamllint-github-action](https://github.com/marketplace/actions/yamllint-github-action) |
| [![Galaxy release](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/galaxy.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/galaxy.yml) | [publish-ansible-role-to-galaxy](https://github.com/marketplace/actions/publish-ansible-role-to-galaxy) |
| | |
| [![Ansible check debian:latest](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-latest.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-latest.yml) | [check-ansible-debian-latest](https://github.com/marketplace/actions/check-ansible-debian-latest) |
| [![Ansible check debian:stable](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-stable.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-stable.yml) | [check-ansible-debian-stable](https://github.com/marketplace/actions/check-ansible-debian-stable) |
| [![Ansible check debian:buster](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-buster.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-buster.yml) | [check-ansible-debian-buster](https://github.com/marketplace/actions/check-ansible-debian-buster) |
| [![Ansible check debian:sid](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-sid.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-sid.yml) | [check-ansible-debian-sid](https://github.com/marketplace/actions/check-ansible-debian-sid) |
| [![Ansible check debian:stretch](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-stretch.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-debian-stretch.yml) | [check-ansible-debian-stretch](https://github.com/marketplace/actions/check-ansible-debian-stretch) |
| | |
| [![Ansible check ubuntu:latest](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-ubuntu-latest.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-ubuntu-latest.yml) | [check-ansible-ubuntu-latest](https://github.com/marketplace/actions/check-ansible-ubuntu-latest) |
| [![Ansible check ubuntu:bionic](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-ubuntu-bionic.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-ubuntu-bionic.yml) | [check-ansible-ubuntu-bionic](https://github.com/marketplace/actions/check-ansible-ubuntu-bionic) |
| [![Ansible check ubuntu:trusty](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-ubuntu-trusty.yml/badge.svg)](https://github.com/roles-ansible/ansible_role_xrandr_help/actions/workflows/ansible-ubuntu-trusty.yml) | [check-ansible-ubuntu-trusty](https://github.com/marketplace/actions/check-ansible-ubuntu-trusty) |
