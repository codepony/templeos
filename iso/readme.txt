                           TempleOS

You can't do much until you burn a TempleOS CD-ROM from the ISO file
and boot it, or you aim your virtual machine at the ISO file and boot.
TempleOS files are compressed and the source code can only be 
compiled by the TempleOS compiler... which is available when you boot
the CD-ROM.  TempleOS is 100% open source with all source present.

TempleOS is 64-bit and will not run on 32-bit hardware.

TempleOS may require you to enter I/O port addresses for the CD-ROM drive
and the hard drive.  In Windows, you can find I/O port info in the
Accessories folder, System Tools, System Info, Hardware Resources, 
I/O ports.  Look for and write down "IDE", "ATA" or "SATA" port numbers.
Then, boot the TempleOS CD and try all combinations.  (Sorry, it's too
difficult for TempleOS to figure-out port numbers, automatically.)

The source code can also be found at the TempleOS web site, 
http://www.templeos.org but cannot be compiled outside TempleOS because
it's HolyC, a nonstandard C/C++ dialect, and asm.
