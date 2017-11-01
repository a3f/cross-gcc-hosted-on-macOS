# Cross ARM/MIPS GCC Toolchains for macOS

Host system is `x86_64-apple-darwin16`. Targets are:

* `mipsel-elf-`: GCC 7.1.0 (no `g++`) with binutils 2.28
* `arm-linux-gnueabihf-`: GCC 7.2.0 (with `g++`) with binutils 2.29 and glibc 2.26 (Linux 4.9.47 headers)

See the [release and associated notes](https://github.com/a3f/cross-gcc-hosted-on-macOS/releases) for tarballs and build configuration.
