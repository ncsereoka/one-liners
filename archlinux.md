# Archlinux

-   List installed packages: `sudo pacman -Q`
-   Delete package along with its dependencies: `sudo pacman -Rns`
-   View package dependency tree (`<package_name>` depends on ...): `pactree <package_name>`
-   View reversed packaged dependency tree (`<package_name>` required by ...): `pactree -r <package_name>`
-   Delete package cache, keeping only one version: `sudo paccache -rk1`
-   Downgrade glibc `sudo pacman -U https://archive.archlinux.org/packages/g/glibc/glibc-2.38-2-x86_64.pkg.tar.zst https://archive.archlinux.org/packages/l/lib32-glibc/lib32-glibc-2.38-2-x86_64.pkg.tar.zst`
-   Clean journal (retain only the past two days) `journalctl --vacuum-time=2d`
