OpenCM9.04 bootloader fixer
===========================

If you bought your OpenCM before ~June 2014, its is likely to have a bootloader
limited to 57K.

To fix that, you can follow the simple procedure:

* Load the sketch "bootloader_fixer" on your board
* Hold the board button, and push the reset one, now release the board button
* Send any simple sketch on your board
* It's done!
