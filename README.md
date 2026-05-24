# tty-clock-git — ALARM PKGBUILD

Builds [tty-clock-git](https://aur.archlinux.org/packages/tty-clock-git) (by [eclairevoyant](https://aur.archlinux.org/account/eclairevoyant)) for **Arch Linux ARM** (aarch64).

Every push to `main` triggers a GitHub Actions build inside an Arch Linux ARM container. The resulting `.pkg.tar.*` package is uploaded as a build artifact.

## Build manually

```sh
git clone https://github.com/AnmiTaliDev/tty-clock-alarm
cd tty-clock-alarm
makepkg -si
```
