Logiconf
==================
Linux alternative for the Logitech Gaming Software.

![screenshot1](https://github.com/dslul/logiconf/blob/master/screen1.png) ![screenshot2](https://github.com/dslul/logiconf/blob/master/screen2.png)


Currently, it is tested with the G402 Gaming Mouse, but it should also work with others. Please open an issue if you encounter any problem.

INSTRUCTIONS:
===================

`git clone https://github.com/dslul/logiconf`

`cd logiconf`

`mv 99-hidraw-logitech-g402.rules /lib/udev/rules.d/99-hidraw-permissions.rules`

Unplug and plug the mouse. Now you can start the program!
