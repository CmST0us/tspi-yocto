# Taishan-Pi Yocto Project

## How to clone

`git clone --recursive git@github.com:CmST0us/tspi-yocto.git`

## Setup Youcto

`source poky/oe-init-build-env`

## Build weston-core-image

`bitbake core-image-weston`


## Flash Image

`./rkflash.sh update`