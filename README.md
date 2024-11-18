# PIC64GX Yocto Manifests

This repository provides manifests to build the [PIC64GX Yocto BSP](https://github.com/pic64gx/meta-pic64gx-yocto-bsp/tree/pic64gx).

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
$ repo init -u https://github.com/pic64gx/pic64gx-yocto-manifests.git -b <branch name> -m default.xml
```

## Examples

To download the **main** branch:

```bash
$ mkdir yocto-dev && cd yocto-dev
$ repo init -u https://github.com/pic64gx/pic64gx-yocto-manifests.git -b main -m default.xml
```

For instructions on how to setup and use the Yocto BSP please refer to the [PIC64GX Yocto BSP README](https://github.com/pic64gx/meta-pic64gx-yocto-bsp/blob/pic64gx/README.md).