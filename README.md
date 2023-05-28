# Public-esp32-rangehood-controller
This is a Home Assistant / esphome / esp32 controller for a kitchen rangehood with 3 speed fan using lilygo esp32 x4 relay
Using hardware https://www.aliexpress.com/item/1005003161500835.html - LILYGO® TTGO T-Relay ESP32 Wireless Module DC 5V 4 Groups Relay

Note interlock is 2000ms, in use a lot shorter time might be better.

This has 4 relays.  

relay 1 is for the halogen lights.
relay2 is for slow speed
relay3 is for medium speed
relay4 is for high speed

2, 3 and 4 are interlocked as only one can be closed at a time.  Note there really needs to be a mechanical or electrical interlock also. 
