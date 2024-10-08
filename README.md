# meta-example
Yocto recipe example

## Steps to add and bitbake

1. Adding layer in conf/bblayers.conf


  BBLAYERS ?= " \
  ${TOPDIR}/../poky/meta \
  ${TOPDIR}/../poky/meta-poky \
  ${TOPDIR}/../poky/meta-yocto-bsp \
  ${TOPDIR}/../meta-example \
  "
  
2. bitbake 

		bitbake core-image-minimal
		or
		bitbake HelloWorld
