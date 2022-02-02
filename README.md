# Arch patches
A collection of reasonable changes to config files in my Arch Linux
installation. Apply any of them to your files with
    [sudo] patch FILE < FILE.patch
# Notes on some patches
* I use following packages: `dedsec-grub2-theme`, `lightdm-slick-greeter`,
  `zsh-vi-mode`.
* Path to grub theme is hardcoded because I'm a lazy person.
* As per vi-mode, I spoke to the developer and got little to no answer so that
  patch was created
* Cinnamon panel looks better when it is transparent
* Yes, multilib is a valid repo for pacman
* Yes, I live in Russia

<!-- vim:set tw=78: -->
