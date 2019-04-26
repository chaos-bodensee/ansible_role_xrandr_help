 xrandr - Ansible role
==========================

Ansible role to install xrandr to controll your monitor setup.

This is realy helpful, if you are using a display manager (eg. i3wm) that comes without a dedicated display control center (like gnome).

 Default variables:
-----------------
```ini
# do you want a graphical display contol panel like arandr
install_graphical_application: true

# do you want autorandr have installed? 
install_autorandr_application: true
```

 Attention:
-------------
This playbook is only tested on archlinux. Package names on other OSes may be different.
