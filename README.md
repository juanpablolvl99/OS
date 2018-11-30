# OS
> this repo will be used to register my attempt to write a OS from scracth

I'm writing a simple OS encouraged and with the help of this [article](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf).


To run and see what it does, it will need a cpu emulator, I'm using qmeu to load the boot and nasm to compile the boot assembly commands into a hexadecimal bin file.


First find the ```x86_64-softmmu``` dir, that can be in other location depending how you have configured the emulator, and run the following commands.
```
<install-folder-path>/x86_64-softmmu/qemu-system-x86_64 -drive \
  file=<your-boot-file-path>.bin, \
  format=raw --nographic
```
