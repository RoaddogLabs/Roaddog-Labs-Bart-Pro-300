### Roaddog Labs Bart Pro XL Firmware
### 
__Deprecated, DO NOT USE!__

The dev version of the current firmware is Marlin RC7 from the Roaddog Labs fork.

https://github.com/RoaddogLabs/Marlin

This fork is configured specifically for the Roaddog Labs Pro XL.  It's
currently based on Marlin 1.1.0-RC3 that was pushed 01 Dec, 2015.  This build is configured for a Mini Rambo controller using 360 mm x 240 mm print bed and Reprap Discount GLCD display

This build defaults to an induction probe in place of a mechanical Z end stop. The file [Configuration_mechanical_z.txt](./Bart_Pro_XL/Configuration_mechanical_z.txt) contains the settings for using a mechanical end stop in the A position.  To use this configuration rename the file to Configuration.h  and build the firmware.

The [original README.md](Orig_README.md) from the fork.