dmenu - dynamic menu
====================
dmenu is an efficient dynamic menu for X. This is a patched build containing the following patches:

* caseinsensitive
* highlight
* numbers

Additionally four new cmdline parameters are supported, specifying colors for highlighting matches from the **highlight** patch. these are:

* `-hf`  highlight foreground
* `-hb`  highlight background
* `-shf` selected highlight foreground
* `-shb` selected highlight background

Requirements
------------
In order to build dmenu you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


Running dmenu
-------------
See the man page for details.
