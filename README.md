# PolarFire SoC Yocto Manifests

This repository provides manifests to build the [PolarFire SoC Yocto BSP](https://mi-v-ecosystem.github.io/redirects/repo-meta-polarfire-soc-yocto-bsp).

## Install the repo utility

To use the manifests within this repository, the `repo` tool must be installed first.

```bash
$ mkdir ~/bin
$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$ chmod a+x ~/bin/repo
$ PATH=${PATH}:~/bin
```

## Download the Yocto Project BSP

```bash
$ mkdir yocto-dev && cd yocto-dev
$ repo init -u https://github.com/polarfire-soc/polarfire-soc-yocto-manifests.git -b <branch name> -m default.xml
```

## Examples

To download the **master** branch:

```bash
$ mkdir yocto-dev && cd yocto-dev
$ repo init -u https://github.com/polarfire-soc/polarfire-soc-yocto-manifests.git -b main -m default.xml
```

For instructions on how to setup and use the Yocto BSP please refer to the [PolarFire SoC Yocto BSP README](https://mi-v-ecosystem.github.io/redirects/repo-meta-polarfire-soc-yocto-bsp).