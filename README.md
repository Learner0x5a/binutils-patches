# binutils-patches
在较新的glibc环境中编译旧版本的binutils所需的patch.

Patches for old gnu binutils versions to build on newer glibc environments.

# 测试环境
Linux 5.4.0-59-generic

Ubuntu 18.04.5 LTS

gcc version 7.5.0 (Ubuntu 7.5.0-3ubuntu1~18.04)

GNU C Library (Ubuntu GLIBC 2.27-3ubuntu1.2) stable release version 2.27

# configure

./configure --disable-gdb --disable-sim --disable-readline --disable-gdbserver --disable-werror
