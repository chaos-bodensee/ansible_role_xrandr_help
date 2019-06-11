 xrandr - Ansible role
==========================

<a href="https://galaxy.ansible.com/do1jlr/xrandr-help"><img width="80px" src="https://galaxy.ansible.com/assets/galaxy-logo-02.svg"/></a>

### Get it directly from Ansible Galaxy 
```bash
$ ansible-galaxy install do1jlr.xrandr-help
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
