# Hackintosh For Every PC/Laptop
This build running on MacOs X 10.13.4

![Alt text](https://ivanov-audio.com/wp-content/uploads/2014/01/Hackintosh-Featured-Image.png)

# Require
    1. Cpu above or equal Haswell

# Know problems
    1. HDMI Audio problem

# DSDT Patch
    This build still need your DSDT patch
    1. ACPI/Battery patch
    2. Fix _WAK Arg0 v2
    3. USB _PRW 0x6D Skylake (insant wake) for sleep fix (if you have above Skylake)
    4. Shutdown fix v2
    5. Rename _DSM methods to XDSM
    6. All your OEM patch

# Note
    1. This build isn't include your wifi and bluetooth kext
    2. This build using vodooHDA, if you have your AppleHDA patch, just remove it from clover