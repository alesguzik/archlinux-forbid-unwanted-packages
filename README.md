# Forbid unwanted archlinux packages

This repo contains PKGBUILD you may use
to forbid installation of packages you don't want.

## Usage

Edit `conflicts` section to contain packages you hate and then

    $ makepkg
    $ sudo pacman -U FORBID_UNWANTED_PACKAGES-1.0-1-any.pkg.tar.xz

Enjoy!
