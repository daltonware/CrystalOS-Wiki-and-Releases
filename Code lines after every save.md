July 24th, 2026 1:46 PM

boot.asm = 62 lines
main.c = 159 lines
io.c = 31 lines
keyboard.c = 25 lines
mouse.c = 76 lines
memory.o = not confirmed, not supported by the code editor i'm using
linker.ld = 38 lines
Makefile = 44 lines
font.h = 90 lines
memory.c (i DO NOT want any meme here but...) = 67 lines
keyboard.c = 25 lines
mouse.c = 76 lines
vga.c = nothing for now
compositor.c = nothing for now
window.c = nothing for now
bmp_reader.c = nothing for now
kernel.bin = just a bin file, not a code file
grub.cfg = 25 lines

TOTAL: 718 confirmed code lines


##############################################################


July 24th, 2026 3:22 PM

(NOW THE FOLDERS ARE INCLUDED :D)

(i took around 15 minutes just to write this)

src/boot/boot.asm = 62 lines
src/kernel/main.c = 168 lines
src/kernel/io.h = 31 lines
src/kernel/keyboard.c = 25 lines
src/kernel/mouse.c = 76 lines
linker.ld = 38 lines
Makefile = 46 lines
src/kernel/font.h = 90 lines
src/kernel/memory.c = 67 lines
iso_root/boot/grub/grub.cfg = 25 lines
src/kernel/interrupts.h = 27 lines
src/kernel/interrupts.c = 81 lines

TOTAL: 736 confirmed code lines

##############################################################

July 24th, 2026 almost 8:32 PM (last save)

src/boot/boot.asm = 62 lines
src/kernel/main.c = 221 lines
src/kernel/io.h = 31 lines
src/kernel/keyboard.c = 25 lines
src/kernel/mouse.c = 76 lines
linker.ld = 38 lines
Makefile = 46 lines
src/kernel/font.h = 90 lines
src/kernel/memory.c = 67 lines
iso_root/boot/grub/grub.cfg = 25 lines
src/kernel/interrupts.h = 27 lines
src/kernel/interrupts.c = 81 lines

TOTAL: 789 confirmed code lines

CORRECTION: I REMOVED 3 LINES OF THE main.c AT 8:48 PM BECAUSE I GOT AN ERROR WHILE "ASSEMBLING THE OS" WITH make clean AND make run AND I'M GONNA TEST IT NOW (make clean is used to remove old output files and the make run is to assemble the codes into the output files and run the OS on QEMU, and make is just a short version of make run but it just assembles and does not run the OS.). SO THE TOTAL CONFIRMED CODE LINES IS 786
