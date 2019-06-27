=======
# bytes at work AG BSP base files for stm32mp1 based modules.

This repository is intended to setup a working Yocto Project environment to
build software for byteDEVKIT by [bytes at work AG](https://www.bytesatwork.ch).

## Usage

This repository is used with [meta-bytesatwork](https://github.com/bytesatwork/meta-bytesatwork) and [meta-bytesatwork-st](https://github.com/bytesatwork/meta-bytesatwork-st).

Example:

	MACHINE=bytedevkit DISTRO=poky-bytesatwork EULA=1 . setup-environment build

Please have a look at the mentioned repositories for possible combinations of
images, machines and distros.

For an easier setup, have a look at
[bsp-platform-st](https://github.com/bytesatwork/bsp-platform-st).
