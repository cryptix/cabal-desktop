# Cabal Desktop

> Desktop client for cabal, the p2p/decentralized/offline-first chat platform.

<center><img width="1552" alt="Screen Shot 2020-06-05 at 10 29 00 AM" src="https://user-images.githubusercontent.com/40796/83952659-2314ec80-a808-11ea-8074-619ece6201e3.png"></center>

## Install

### Download the latest release

https://github.com/cabal-club/cabal-desktop/releases/

### Build from source

```
$ git clone https://github.com/cabal-club/cabal-desktop
$ cd cabal-desktop

$ yarn install             # install dependencies
$ yarn start               # start the application
```

### Download from AUR
https://aur.archlinux.org/packages/cabal-desktop-git/

### Updating MacOS DMG background image
```
tiffutil -cathidpicheck cabal-desktop-dmg-background.jpg cabal-desktop-dmg-background@2x.jpg -out dmg-background.tiff
```

## Distribute

build for current platform:

```
$ yarn run dist
```

build for [multiple platforms](https://www.electron.build/multi-platform-build#docker):

```
$ ./bin/build-multi
```

## How to Contribute

### Formatting Rules

This repository is formatted with [StandardJS](https://standardjs.com/) (there is a [vscode](https://marketplace.visualstudio.com/items?itemName=chenxsan.vscode-standardjs) plugin).
