# MiniBootloader

## Environment
* Assembler: MASM 5.0
* Test OS: MS-DOS 6.22
* Test Virtual Machine: VMWare Workstation 16

## Example Installation (VM environment)
1. Rename MiniBootloader.asm as minibl.asm (MS-DOS cannot display long file name).
2. Use command `masm minibl;` to generate object file.
3. Use command `link minibl;` to link.
4. Insert a clean and formatted virtual floppy disk.
5. Use command `minibl` to start installation, bootloader will be copied to virtual floppy disk.

## Boot
* Boot the VM, set primary bootable device as virtual floppy disk and enjoy.

## Notes
* Logically, this BL should works with PC in real life, but not tested, use at your own risk.
* Ideally, you can change the code to install BL into hard disk (?).

## Screenshot
* Main Screen  
![MainScreen](https://github.com/AcidCannon/MiniBootloader/raw/main/Screenshots/MainScreen.png)

* Read Date and Time From BIOS  
![BiosDate](https://github.com/AcidCannon/MiniBootloader/raw/main/Screenshots/BiosDate.png)

* Set Date and Time for BIOS  
![SetDate](https://github.com/AcidCannon/MiniBootloader/raw/main/Screenshots/SetDate.png)