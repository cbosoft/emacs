### [Emacs](https://www.gnu.org/software/emacs/)

#### Install using MELPA

    M-x package-install <RET> dracula-theme

#### Install using Homebrew

    brew install dunn/emacs/helm

#### Install manually

Add the emacs theme files to `~/.emacs.d/themes`.

To load a theme add the following to your init.el

    (add-to-list 'custom-theme-load-path "~/.emacs.d/themes")
    (load-theme 'dracula t)
