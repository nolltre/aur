# Collection of `PKGBUILDs`

This is a collection of `PKGBUILD` files (and patches) for various projects that were unavailable in the Arch User Repository (AUR).

## Currently available
- [Satpi](satpi/) from [Barracuda09](https://github.com/Barracuda09/SATPI)

## To build
- Clone this repository
- Change directory into whichever package you want to build
- Run `makepkg -s` to install build dependencies
- Install with `sudo pacman -U <pkgname>`

You can also build and install in one go with `makepkg -si`
