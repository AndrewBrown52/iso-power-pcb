# ISOpowerProject
 Remote power control board for ISO experiment containers, used for remote labs projects
![ISOpower](https://user-images.githubusercontent.com/97303986/158610534-c0feec4a-f649-47c7-bc71-ae8b51f817a3.png)
![ISOpowerPCBdesign](https://user-images.githubusercontent.com/97303986/158610818-84cbbe2c-e711-4a15-b655-8e105aa62b4e.png)

## Use

### prog_power_select

- Jumper is used for power routing during programming
- Cut trace to main and solder USB to center to enable USB power during programming.
- Ensure to remove USB side and replace main for normal use



## Issues

1. Tx & Rx Pin swapped on CH340 - aTmeGA328P
 - To enable USB communication, reverse pins 2 & 3
