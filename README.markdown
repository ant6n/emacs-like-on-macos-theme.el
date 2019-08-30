# emacs-like-on-macos-theme.el for Emacs 24's

A light-on-dark color theme adapted from adapted from jmeldin's [ir-black-theme.el](https://github.com/jmdeldin/ir-black-theme.el), who in turn adapated Todd Werth's [original Textmate theme](http://toddwerth.com/2007/03/29/ir_black-the-last-textmate-theme-youll-ever-need/). The theme was adapted by ideas from [this Stack Exchange question](https://superuser.com/questions/542858/how-to-get-emacs-terminal-theme-for-emacs-app) by nico_c.

The desire is to have an emacs theme that matches what is shown on in emacs on MacOs. In MacOs, emacs colors are funky, but once you're used to it it's hard to change.

## Installation

The easiest way is to install it through [MELPA](http://melpa.milkbox.net/) with 
`M-x package-install RET ir-black-theme`. Otherwise, see the commentary in 
`ir-black-theme.el` for manual installation instructions.

## Usage

After installing it:

1. `M-x load-theme RET emacs-like-on-macos`
2. Don't like it? Type `M-x disable-theme RET emacs-like-on-macos` to restore your
   previous theme.
