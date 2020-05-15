# MaaXBoard i.MX Repo Manifest

## How to

### Install repo

To use this manifest repo, the 'repo' tool must be isntalled first.

```bash
$ mkdir ~/bin
$ curl http://commondatastorage.googleapis.com/git-repo-downloads/repo  > ~/bin/repo
$ chmod a+x ~/bin/repo
$ PATH=${PATH}:~/bin
```

### Sync Repo

```bash
$ mkdir imx-yocto-bsp
$ cd imx-yocto-bsp
$ repo init -u https://github.com/ahnniu/imx-manifest -b imx-linux-sumo -m maaxboard-4.14.78-1.0.0.xml
$ repo sync
```

### Build

Follow the README in the meta-maaxboard repo