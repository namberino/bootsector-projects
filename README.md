# Bootsector experimentation

This directory is some mini bootsector projects for me to get used to programming the bootsector.

Each projects is a practice for programming the actual bootsector

# Project directories

[32bit](32bit) contains bootsector code for 32-bit protected mode

[disk](disk) contains bootsector code for accessing the hard disk from the bootsector

[functions](functions) contains bootsector code for printing and formatting

[memory](memory) contains bootsector code for handling the bootsector's location in memory

[print](print) contains bootsector code for printing to the screen from the bootsector

[segment](segment) contains bootsector code for segmentation in bootsector

[stack](stack) contains bootsector code for working with the stack from the bootsector

# Compile and run

Compile this with `nasm`: `nasm -f bin <filename.asm> -o <filename.bin>`

Emulate this with `qemu`: `qemu-system-x86_64 <filename.bin>`
