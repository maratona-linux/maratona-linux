# Maratona Linux

Makes all Maratona-Linux components available in their stable versions using git
submodules.

## About

This repository is a super-project which contains all Maratona Linux components
in the versions used in the Maratona Linux's stable PPA. To clone this
repository, you must clone it and initialise its submodules. With a recent Git,
you may just:

```
git clone --recurse-submodules https://github.com/maratona-linux/maratona-linux.git
```

If you have already cloned this project, it is advisable to run:

```
git submodule init
git submodule update
```

## Installing Maratona Linux Packages

If you wish to install Maratona Linux packages on top of an Ubuntu 22.04, you
may use our public PPA repositories. If you intend to install the stable version
of Maratona Linux, please execute the following commands that may require
elevated privileges:

```
add-apt-repository ppa:icpc-latam/maratona-linux
apt update
apt install maratona-desktop
```

If you wish to install the unstable development version of Maratona Linux, a
similar set of commands is necessary:

```
add-apt-repository ppa:icpc-latam/unstable
apt update
apt install maratona-desktop
```

If some error occurs or if you have a request, please open a ticket (issue) in
the Git repository of the affected package. You can find the URL for each
package's repository in the `.gitmodules` file.

If you are not able to determine which package (component) caused the unexpected
behaviour, feel free to open a ticket in this repository.

## Packages' Contents

The following packages are provided in each repository:

- maratona-background
- maratona-fancy-tools
- maratona-firewall
- maratona-intellij-clion
- maratona-intellij-idea
- maratona-intellij-pycharm
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
  - maratona-editores-external
  - maratona-vscode-extensions
  - maratona-kotlin-doc
- maratona-usuario-icpc
- maratona-visual-studio-code