editable-emacs-keymaps-pdf
==========================

**Introduction**

This is a PDF to visually show your Emacs keymappings; the form fields are editable and color coded.  I have only tested this on two different PDF readers -- Evince and Acrobat Reader.  It does not work on Evince, and does work on Acrobat Reader (both Linux and Windows).  See http://lshort.github.io/emacs-init/KeyMap.pdf for an example of the two-page format.

I would appreciate any feedback you might have.  At this point, this work is in an alpha release.  You can reach me at lee.o.short . gmail @ com (or something much like that).

**How to fill the fields**

The keymap leaves space for 5 slots per key.  I use those 5 slots for C-<key>, C-x C-<key>, C-c C-<key>, C-h C-<key>, and M-<key>. So my "Key" section looks like:

Key
   C-
   C-x C-
   C-c C-
   C-h C-
   M-

And one of my key entries looks like:

F
   move-end-of-line
   zap-to-char
   point-to-register
   -
   hippie-expand

Together, these indicate that C-f is bound to move-end-of-line, C-x C-f is bound to zap to char, C-c C-f is bound to point-to-register, there is no binding for C-h C-f, and M-f is bound to hippie-expand.
