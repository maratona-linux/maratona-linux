# Maratona Linux

Checkout all Maratona-Linux components at once by using git submodule.

## About

This is a superproject which contains all Maratona Linux components. To
clone this repository you must initialize the submodules, with a recent git
you may just

```
git clone --recurse-submodules https://github.com/maratona-linux/maratona-linux.git
```

## Installing Maratona Linux Packages

If you want to install Maratona Linux packages on top of a Ubuntu 18.04, you
may use our public ppa repositories by simply running:

```
sudo add-apt-repository ppa:icpc-latam/maratona-linux
sudo apt-get install maratona-desktop
```

If some error occurs or if you have some request, please open a ticket
within the git repository of the package.

Below it is specified what packages are provided in each repository:

- maratona-background
- maratona-firewall
- maratona-flatpak-common
- maratona-kairos
- maratona-meta
    - maratona-desktop
    - maratona-conflitos
    - maratona-essential
    - maratona-desktop-latam
    - maratona-task-data
- maratona-submission
- maratona-team-tools
    - maratona-linguagens
    - maratona-linguagens-doc
    - maratona-editores
    - maratona-editores-flatpak
    - maratona-vscode-extensions
    - maratona-kotlin-doc
- maratona-usuario-icpc