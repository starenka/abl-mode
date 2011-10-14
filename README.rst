========
abl-mode
========

The abl-mode is for python programmers who develop using virtual
environments, version control branches and unit tests. To install
abl-mode, put abl.el on your elisp path, and include the following in
your emacs configuration file:

(require 'abl)

If you want to activate abl-mode automatically, add the following to
your configuration:

(add-hook 'find-file-hooks 'abl-mode-hook)

You can replace find-file-hooks with python-mode-hook if you want to
activate abl-mode only for python files.

=======================================
Commands and their default key bindings
=======================================

Here is a list of the most important functions and their keybindings:

C-c t    Run the test entity at point
C-c u    Re-run last test entity
C-c r    Start web server for project
C-c s    Run python shell for the current virtual env

=============
Customization
=============

Have a look at the abl mode cheatsheet in the project repository for a
complete list of customization options and commands.
