# Isoduino Mega 640/1280/2560

__Author:__ Bei Chen Liu

__Description:__ An isolated Arduino Compatible development board specially designed for robotics operation.

__Features:__
* Isolated UART to protect computer from motor noise.
* Switching regulator to allow a greater voltage input range.

## Changelog:

### Version 1.3B
- Remove oscillator resistor
- Add better routing for the reset line
- Reduce the board size by a little to make it fit in 10cm

### Version 1.3
- Change the non isolated mode name from 'USB Mode' to 'Bypass Mode'
- Add a power mux to handle power switching from isolated mode to bypass mode
- Add power LED for mode indication
- Change user LED behavior: LED will turn on if the pin is high
- Update components and front silk
- Add back silkscreen

## 3D Render:
<img src="isoduino-mega_lay_3d1.png" width="400">

## Schematic:
<img src="isoduino-mega_sch_s1.jpg" width="400"><br>
<img src="isoduino-mega_sch_s2.jpg" width="400"><br>
<img src="isoduino-mega_sch_s3.jpg" width="400">

## Layout:
<img src="isoduino-mega_lay_l1.jpg" width="400"><br>
<img src="isoduino-mega_lay_l2.jpg" width="400">
