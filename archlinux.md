# Archlinux

-   List installed packages: `sudo pacman -Q`
-   Delete package along with its dependencies: `sudo pacman -Rns`
-   View package dependency tree (`<package_name>` depends on ...): `pactree <package_name>`
-   View reversed packaged dependency tree (`<package_name>` required by ...): `pactree -r <package_name>`
-   Delete package cache, keeping only one version: `sudo paccache -rk1`
