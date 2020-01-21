# Emacs-SML-Setup

Setup foer Ubuntu 
sudo apt install smlnj  
M-x package-install sml-mode  
https://courses.cs.washington.edu/courses/cse341/11au/sml-emacs.html

## Emacs Errors:
Cannot verify signature  
Add following to .emacs  
(require 'package) 
(setq package-check-signature nil)

Restart emacs.

M-x package-install gnu-elpa-keyring-update

Then remove the lines. Restart emacs.
