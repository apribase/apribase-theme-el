# apribase-theme-el

Emacs custom face for apribase.

![apribase-theme.el](https://farm4.staticflickr.com/3690/8808034538_f3ef9262d2_z.jpg) 

## Installation

Download `apribase-theme.el` to the directory `~/.emacs.d/themes/`.
Add this to your `~/.emacs.d/init.el`

```lisp
(add-to-list 'custom-theme-load-path (expand-file-name (concat user-emacs-directory "themes")))
(load-theme 'apribase t)
```
