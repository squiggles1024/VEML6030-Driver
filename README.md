# VEML6030

Simple VEML6030 Ambient Light Sensor Driver

To use, include .c and .h files in your project.
The user must:
1. Create a VEML6030_Handle_t instance.
2. Create a VEML_InitSettings_t struct with the desired device settings. It is recommended the user reference the data sheet for setting details.
3. Provide a Low Level IO Driver structure "VEML6030_IO_t". At a minimum, this must include a "Read" and "Write" function. Unused function pointers should be set to NULL.
