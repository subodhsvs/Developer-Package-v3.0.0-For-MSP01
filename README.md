# Developer-Package-v3.0.0-For-MSP01
LinuxSourceCode and buildwith DTS configuration for MSP01 board

This is patched and updated code for working with MPS01.

Application with Generic buffer aproach also works with this code. 

The code is derived from openSTLinux release_v3.0.0 

# Fetch this code and compile with SDK compatible with above release

flash the DTBS and lib/modules to the STM32MP157F-DK2 board (MSP01 expansion board conected )

boot the boards > synchronise module dependencies and reboot.

iio devices will created in sysfs 

Use the Generic Buffer example from Github : https://github.com/subodhsvs/GenericBuffer_CodeExample.git
copy in the source folder of the Standard folder structure of your developer packaage 
cross-compile and use as directed in its README file


