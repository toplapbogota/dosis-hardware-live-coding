# dosis-hardware-live-coding
A symbol library for Inkscape with footprint of different hardware for laser cutting and hadware prototyping. 

## Reference

|element|template|svg|name|
|--|--|--|--|
|![](./hardware/gear_box_dc_motor_yellow.webp)|![](./hardware/gear_box_dc_motor_yellow_template.webp)|![](./hardware/exported_svgs/gear_box_dc_motor_yellow.webp)|Yellow Gear Box DC Motor|
|![](./hardware/gear_box_dc_motor_yellow_shaft.webp)|![](./hardware/gear_box_dc_motor_yellow_template.webp)|![](./hardware/exported_svgs/gear_box_dc_motor_yellow_shaft.webp)|Yellow Gear Box DC Motor **Shaft**|
|![](./hardware/stepper_motor_28bjy48.webp)|![](./hardware/stepper_motor_28bjy48_template.webp)|![](./hardware/exported_svgs/stepper_motor_28bjy48.webp)|28BYJ-48 Stepper Motor|
|![](./hardware/stepper_motor_28bjy48_shaft.webp)|![](./hardware/stepper_motor_28bjy48_shaft_template.webp)|![](./hardware/exported_svgs/stepper_motor_28bjy48_shaft.webp)|28BYJ-48 Stepper Motor **Shaft** |
|![](./hardware/dc_motor_big.webp)|![](./hardware/dc_motor_big_template.webp)|![](./hardware/exported_svgs/dc_motor_big.webp)|DC Motor Big|
|![](./hardware/servo_motor.webp)|![](./hardware/servo_motor_template.webp)|![](./hardware/exported_svgs/servo_motor.webp)|Servo Motor|
|![](./hardware/arduino_uno.webp)|![](./hardware/arduino_uno_template.webp)|![](./hardware/exported_svgs/arduino_uno.webp)|Arduino Uno|
|![](./hardware/dc_motor_driver.webp)|![](./hardware/dc_motor_driver_template.webp)|![](./hardware/exported_svgs/dc_motor_driver.webp)|DC Motor Driver|
|![](./hardware/relay_module_x_2.webp)|![](./hardware/relay_module_x_2_template.webp)|![](./hardware/exported_svgs/relay_module_x_2.webp)|Relay Module X 2|
|![](./hardware/arduino_nano.webp)|![](./hardware/arduino_nano_template.webp)|![](./hardware/exported_svgs/arduino_nano.webp)|Arduino Nano|
|![](./hardware/servo_horn_7_6.webp)|![](./hardware/servo_horn_7_6_template.webp)|![](./hardware/exported_svgs/servo_horn_6_7.webp)|Servo Horn 6/7|
|![](./hardware/servo_horn_7_6.webp)|![](./hardware/servo_horn_7_6_template.webp)|![](./hardware/exported_svgs/servo_horn_6_6.webp)|Servo Horn 6/6|
|![](./hardware/metal_angle_L_shape_1_2.webp)|![](./hardware/metal_angle_L_shape_1_2_template.webp)|![](./hardware/exported_svgs/metal_angle_L_shape_1_2.webp)|Metal L 1/2 "|

# Installation

Download the code: it can be either done by cloning the repository or downloading the zip file.

##download 

In order to download the inkscape symbols, you can either clone the repository or download the zip file.

### clone

```bash
git clone https://github.com/dosis-hardware/dosis-hardware-live-coding.git
``` 
### download zip

Do click on the green button labeled with the word code.

![alt text](./assets/code-button.png)

This opens a drop down menu in which you may click the **download zip** item

![alt text](./assets/download-zip.png)

## move the main file

The main file is [panel-mount-electronics.svg](./inkscape-symbols/panel-mount-electronics.svg) and it should be moved to the inkscape user symbols folder. 

You can check which the inkscape symbols folder is by opening **inkscape** and at the application menus:
- on windows and linux go to Edit > Preferences > System.
- on macos go to Inkscape > Preferences > System

 The path to the symbols folder is listed under **User symbols** and there is a button to open it.

So if you cloned the repository, just move the file to the user symbols folder. If you downloaded the zip, unzip it and move the file to the user symbols folder.

[version en español de las instrucciones](./README.es.md)

## Note 
Installation instructions are important because every time we update the main file we will need to move it to the inkscape user symbols folder.