# ZyboZ7-20_PYNQBOOT
ZyboZ7-20 PYNQ Liunx boot files and methods

# How To Boot???
1.  Prepare PYNQ_rootfs in https://github.com/Xilinx/PYNQ/releases (in my case, PYNQ-Z2-2.3 SDCard image)
2.  Write the image to SDCard using dd. (ex. sudo dd if=./<PYNQ_IMAGE> of=/dev/sdx status=progress)
3.  Copy and Paste Boot files to BOOT partition. (ex. cp BOOT.bin devicetree.dtb uEnv.txt uImage <BOOT_DIRECTORY>)
4.  Done!!

# This Rerepository Built using...
1. Xilinx PYNQ sdbuild tools(https://github.com/Xilinx/PYNQ/tree/master/sdbuild)
2. ikwzm's U-BOOT image for ZyboZ7-20 (https://github.com/ikwzm/FPGA-SoC-U-Boot-ZYBO-Z7)
