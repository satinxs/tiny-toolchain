# tiny-toolchain

This is a tiny toolchain to make C programs, for people who are on Windows and don't want to download a full C/C++ toolchain (mingw, msys2, clang, etc).

Note: This will only work for C, since the compiler included is the [TinyCCompiler](https://bellard.org/tcc/) by Fabrice Bellard, which only supports C.

How to use: unzip the [zip](https://github.com/satinxs/tiny-toolchain/archive/master.zip) file into a folder and add said folder to PATH (you can alternatively `git clone` it to the desired folder instead of unzipping).