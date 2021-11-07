# The GCC compiler assembly with MinGW-w64, for Windows, i686/x86_64

Built by [mingw-builds](https://github.com/niXman/mingw-builds) with the command:

```
./build \
--buildroot=/home/<user>/work \
--mode=gcc-<version> \                # gcc-11.2.0
--enable-languages=c,c++ \
--arch=ARCH \                         # i686|x86_64
--exceptions=EXCEPT \                 # dwarf|seh -- dwarf for i686, seh for x86_64
--threads=posix \
--rt-version=<MinGW-w64-version> \    # v9
--with-default-msvcrt=msvcrt \        # msvcrt.dll, native version in Windows, there is since Windows XP
--rev=1 \
--bin-compress \
--jobs=4 \

```
