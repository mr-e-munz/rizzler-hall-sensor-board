# Eru's Rizzler Hall Sensor Board
## Design Overview
 - This is an alarm system using a hall effect sensor to detect when the door opens, and then create a sound.
 - There will be a module installed in the door to detect when the door is opened or closed.
 - It will be a BLE module which will broadcast the door state in its advertising manufacturer data
 - There will be a Raspberry Pi that listens to the manufacturer data, and will turn a buzzer on when the door is open, and off when it is closed.

## Design Requirements
 - Battery powered
 - LiSO-Cl2
 - Nominally use Tadiran AA-size SL-360 battery (3.6V) - see: https://tadiranbatteries.de/wp-content/uploads/2023/02/SL-360.pdf
 - Minimum time between battery changes = 2 years.
 - Raspbery Pi zero case - Core SKU: CE06235 - see: https://core-electronics.com.au/slim-case-for-raspberry-pi-zero.html
 - Raspberry Pi Zero W - Core SKU: CE04754 - see: https://core-electronics.com.au/raspberry-pi-zero-w-wireless.html

## Components
 - use TCS40DLR for hall effect sensor
 - use RF Star RF-BM-ND04C for BLE SoC module - see: https://www.szrfstar.com/product/BLE_Nordic_nRF52810-en.html


































