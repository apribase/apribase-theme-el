# apribase-theme-el

Emacs custom face for apribase.

## Installation

Download `apribase-theme.el` to the directory `~/.emacs.d/theme/`.
Add this to your `~/.emacs.d/init.el`

```lisp
(add-to-list 'custom-theme-load-path (expand-file-name (concat user-emacs-directory "themes")))
(load-theme 'apribase t)
```
