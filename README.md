# Emacs-SML-Setup

Setup foer Ubuntu
sudo apt install smlnj
M-x package-install sml-mode
https://courses.cs.washington.edu/courses/cse341/11au/sml-emacs.html

## Emacs Errors:
Cannot verify signature
Add line to .emacs
(require 'package)
(setq package-check-signature nil)

M-x package-install
