What I can do with the RPI Pico:

The Leapster2 has a USB port, and an SD card slot.

While it would be very slow, I could run some CDB commands on the Pico through the USB port to unlock the drives and then transfer to the SD that way. 

When the Leapster2 is connected to a standard PC, the PC sees 2 devices. The RAM and the SD.

You can send the same Didj SCSI commands for unlocking and locking to the RAM or SD.

Only one problem though.

RAM is wiped on restart, meaning that you CAN'T mod the L2 that way (at least I think)

I could probably use the Pico to overwrite this, but that would probably require some coding on the Leapster.

The SD, however, has no such issue and you can read/write to it with ease.

The Leapster2 has an option where you can boot any SD card game, is it possible to make an SD card game that uses the Pico?

<del>Please note that you would have to find some way to bypass the USB connected screen, if it ever becomes a problem.</del>

Edit: the USB connected screen is only a problem if it's not a host device, this means that any other usage is not a problem.
