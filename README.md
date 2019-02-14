# TI 84+ Serial Routines

This is a dump of code I wrote to let TI-84+ graphing calculators communicate
with other devices using asynchronous serial protocols. It's in an unorganized,
unedited state but I hope that it gives some hints for anyone interested in
doing similar.

To assemble and pack one of the programs into a calculator application use tasm
and devpac8x.

1. `tasm -80 -i -b something.z80 something.bin`
2. `devpac8x something`
