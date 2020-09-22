# Connect to you ESP32 device

This section provides guidance how to establish serial connection between ESP32 and MacBook.

## Connect ESP32 to MacBook
Connect the ESP32 board to the MacBook using the USB cable.

## Check port on MacOS
To check the device name for the serial port of your ESP32 board, run this command two times, first with the board unplugged, then with plugged in. The port which appears the second time is the one you need:

```
ls /dev/cu.*
```

example of a port ```/dev/cu.SLAB_USBtoUART```