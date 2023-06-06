# AnyDLKM

## Objective
To copy/replece kernel modules into vendor_dlkm/lib/modules/*.ko

## Prequistes
1. Samsung phone which is rooted and support TWRP.
1. Linux Kernel 5.10
1. Disabled knox, full disk encryption.

## Tested devices
1. Samsung Galaxy Z Fold4 (F936B)

## Instruction
1. Copy loadable kernel modules into `modules` folder.
1. `zip -r9 AnyDLKM.zip * -x .git README.md *placeholder`
1. Reboot into TWRP recovery mode.
1. Copy `AnyDLKM.zip` into phone and install it.
