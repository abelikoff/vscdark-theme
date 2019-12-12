# vscdark-theme

Visual Studio Code Dark+ like theme for Emacs 24.

(created with [Emacs Theme Creator](http://emacs-theme-creator.appspot.com)).


## Screenshot

![Screenshot](https://github.com/abelikoff/vscdark-theme/raw/master/screenshot.png)


## Installation

### Using package managers

Configure MELPA package repository in `~/.emacs` (or `init.el`):

    (setq package-archives '(("gnu" . "http://elpa.gnu.org/packages/")
                             ("melpa" . "http://melpa.org/packages/")))
    (package-initialize)


Install the package:

    M-x package-install vscdark-theme


Load the theme:

    (load-theme 'vscdark)
