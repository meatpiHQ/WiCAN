<img src="https://github.com/slimelec/ollie-hw/blob/master/images/mpi_logo.png" width=300>

[www.meatpi.com](https://www.meatpi.com)
---

## [**Programming Examples**](https://github.com/meatpiHQ/programming_examples/tree/master/CAN)

### WiFi/CAN Configuration:
1. Power up the device using the USB cable, or by plugging into the OBD-II connector. 
2. The blue LED will light ON, and a WiFi device access point will start. The SSID will look like: WiCAN_xxxxxxxxxxxx
3. Connect to the SSID using the default password: @meatpi#
4. Using a web browser, go to http://192.168.80.1/ 
5. The status menu shows the device current configuration, if in Ap+Station mode it will show the device IP on your local network if connected successfully.
6. The WiFi menu lets you configure the WiFi parameters. It is recommended that you change the AP access point.
7. The CAN menu allows to choose the protocol set the bitrate and TCP/UPD port number.
8. When ready click submit Changes button and the device will store the configuration reboot immediately.

<img src="https://user-images.githubusercontent.com/94690098/158788439-729c8de4-9961-4d9d-af54-c572cb711273.jpg" width="300" height="600" >

### BUSMaster
You need to download the right version of BUSMaster provided in this [**Link**](https://bit.ly/3yGgGTm) above. Here is how to setup the hardware. 

1. Select VSCom CAN-API by clicking on 'Driver Selection -> VSCom CAN-API"
2. Then Click on 'Channel Configuration -> Advanced' 
3. Fill in the IP and port. **Example: 192.168.80.1:3333**
4. Check the 'Hardware Timestamps' check box.
5. Choose the Baudrate.
6. Click 'OK', then Click the Connect button on the top left corner.
  

<img src="https://user-images.githubusercontent.com/94690098/158798541-0317aa4f-ebf5-4e57-83b0-ea3fefeaf4e9.png" width="350" height="500" >

### Firmware Update
Use the ESP flash tool to update the firmware, just follow the same setting in the picture below. Also "esptool.py" can also be used to flash a new firmware.

<img src="https://user-images.githubusercontent.com/94690098/158790496-31827bf3-4bda-47db-971d-ac1d53ad7972.PNG" width="350" height="600" >

## 3. ReadDash
WiCAN can connect with RealDash using WiFi or BLE. The Protocol and CAN bitrate must be set using the configuration page. BLE is only support on Android and IOS. Windows 10 only supports WiFi connection.

[![Youtube](https://img.youtube.com/vi/qZzDJdLbzR0/0.jpg)](https://www.youtube.com/watch?v=qZzDJdLbzR0)
  



---

© 2022 meatPi Electronics | www.meatpi.com | PO Box 5005 Clayton, VIC 3168, Australia
