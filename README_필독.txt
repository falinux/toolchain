cd ~

mkdir toolchain

cd toolchain

git clone git@192.168.3.13:toolchain/arm-linux-gnueabihf-4-6-3.git

install.sh


####################################################################

#!/bin/sh

tar zxvf arm-linux-gnueabihf-4-6-3.tar.gz

export CC=`pwd`/arm-linux-gnueabihf-4-6-3/bin/arm-linux-gnueabihf-


