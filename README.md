# NVIM latest stable - 0.9.1 for Debian 12 testing (bookworm)

Neovim stable [builded for debian with cpack](https://github.com/neovim/neovim/wiki/Building-Neovim) using the clang/llvm stack from the [official neovim repo](https://github.com/neovim/neovim).

Disclaimer: This package was build ofr testing purposes.

Install with:
`sudo dpkg -i nvim-linux64.deb`

## Compilation details

- Debian clang version 14.0.6
- Target: x86_64-pc-linux-gnu
- Thread model: posix
- Architecture: amd64
- Depends: libc6 (>= 2.34), libgcc-s1 (>= 3.3)

## Prerequisites versions

- ninja-build: 1.11.1
- gettext (GNU gettext-runtime): 0.21
- cmake version 3.25.1
- CMake suite maintained and supported by Kitware (kitware.com/cmake).
- unzip: 6.00
- Lua 5.4.4  Copyright (C) 1994-2022 Lua.org, PUC-Rio
- curl 7.88.1 (x86_64-pc-linux-gnu) libcurl/7.88.1 OpenSSL/3.0.9 zlib/1.2.13 brotli/1.0.9

## Neovim Licence

<a href="https://github.com/neovim/neovim/blob/master/LICENSE.txt">
Copyright Neovim contributors. All rights reserved. 

Apache License Version 2.0, January 2004
</a>
