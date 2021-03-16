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

 Default variables:
-----------------
```ini
# do you want a graphical display contol panel like arandr
install_graphical_application: true

# do you want autorandr have installed?
install_autorandr_application: true

# version management to prevent old playbooks
submodules_versioncheck: true
```

 Attention:
-------------
This playbook is only tested on archlinux. Package names on other OSes may be different.
