Softwares used:



1. STM32CubeIDE
2. STM32CubeMX



Building the firmware:



1. Open the .ioc file in CubeMX for grasping any idea about the pin layout or modifications
2. Then open the CubeIDE and import the project using "Open Projects from the File system"
3. In Import source, give the path of the project folder and add.
4. Press Build to build the firmware.Check whether the build completes within 0 errors.



Flashing the firmware:

1. Open Run->Debug Configurations and select the STM32 Cortex-M C/C++ Application configuration for the project. Verify that the ST-LINK debugger is inserted and selected.
2. Click Debug to download the firmware to the microcontroller.

