# UART to Bluetooth bridge
## Work in progress !
Thist program will act as a transparent relay between UART and Bluetooth.
Not sure yet how BT will exactly be implemented.
Current approach:
- Bluetooth Low Energy Service with RX and TX Characteristic
- sends incrementing value on RX notification
- connect to UART over USB to see debug messages.


