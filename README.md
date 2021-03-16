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
|
