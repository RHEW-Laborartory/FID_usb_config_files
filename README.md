# Linux Instrument Config Files

## 50-usb-serial.rules
This file, properly configured, allows USB devices to be referred to by a given name (aka `SYMLINK`). This is done through the creation of a rule.
Rules typically contain attributes unique to a device, which allows it to be easily identified by the operating system.

__This file needs to be copied to `/etc/udev/rules.d/` in order to work.__

## Currently Defined SYMLINKS in 50-usb-serial.rules for GC-FID:
* "valcoVici6Port",
* "omegaWaterTrap",
* "omegaSampleTrap"
* "redyFlowMeter"
