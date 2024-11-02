# cosmo-sokol

![Build status](https://github.com/bullno1/cosmo-sokol/actions/workflows/build.yml/badge.svg)

Sample sokol+dearimgui application compiled with [cosmopolitan toolchain](https://github.com/jart/cosmopolitan/).

## Build instruction

Until the changes are merged upstream, the following cosmopolitan fork is required: https://github.com/bullno1/cosmopolitan/tree/new-nt-functions.
With cosmocc in your PATH, run `./build`.

Then run `bin/cosmo-sokol`.

Note: On Windows, if you are using a NVIDIA graphic card, you may have to disable "Threaded optimization".

## How it works

TL;DR: dlopen and codegen for Xlib and GL.

TODO: Elaborate.
