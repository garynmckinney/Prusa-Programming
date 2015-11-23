# Prusa-Programming
Directory of prusa programming for 3D printer

This directory contains the source code and instructions for programming the MKS_BASE main board with the firmware to run the Prusa i3 3D printer.

There is one main source code tree and two configuration.h file trees in the directory

One of the configuration.h file trees contains the configuration.h file for the standard bed printer while the other tree is for the large bed printer.  Please don't get them confused when you update your firmware as the large bed configuarion.h file will cause the printer to attempt to print past the standard bed and ruin your prints - it may also cause your auto-leveling function to crash the extruder into the bed since the sensor will be off the end of the bed and unable to detect the bed during the auto-leveling function.

You have been warned!
